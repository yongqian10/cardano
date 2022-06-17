---------------------------------------------------------------------------------------------
-- Transactions
    how signing works

    - what are transactions

        - instruction for modifying the ledger
        - can spend UTXOs
        - can contain certificates
        - can contain metadata
        - can mint/burn tokens
        - can contain scripts(smart contracts or native scripts)



    - unsigned transaction look like (.txbody)

        [
            {
                "0":
                    [
                       // utxo in
                       // ix in
                    ]

                "1":
                    [
                        // utox out to return the change
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
            [
                [
                    0,
                    // script keyhash
                ]
            ],
            // meta data
        ]
