---------------------------------------------------------------------------------------------
-- UTXOs

    - structure

        Public/ Private keys    -? whose pub key used?
            Addresses
                1. UTXOs -
                    Address on Testnet(receiver address on testnet)
                    TxHash  |   TxIx   |   Amount


    -- seq:

        1) UTXO(send with extra ada)
        2) UTXO(return remaining ada)
        3) whole operation can be not signed at all, we just having multiple UTXOs under
           the receiver address(unspend)



    - UTXOs queue
