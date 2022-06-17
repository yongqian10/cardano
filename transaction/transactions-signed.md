---------------------------------------------------------------------------------------------
- signed transaction look like -? who sign the transaction? third party?

        [
            -- front part is the same
            {
                "0":
                    [
                       // utxo in
                       // ix in
                    ]

                "1":
                    [
                        // utxo out to return the change
                        // change
                    ],
                    [
                        // utox out for where to drop the token with minimum token keep fee
                        [
                            // min token keep fee
                            {
                                // policy id
                                {
                                    token name + amount
                                }
                            }
                        ]
                    ]
                "2": //tx fee
                "3": // invalid hereafter
                "9":
                    {
                        // policy to mint
                        {
                            // name and number to mint
                        }
                    }
            },

            -- this part contain signed hash
        ]
