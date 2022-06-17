-----------------------------------------------------------------------------------------------
-- plutus Tx (transaction)
    -- libraies and compiler for compiling Haskell into Plutus Core to form  the on-chain part of a contract app

        - on-chain code
        - compiled into Plutus Core

        - can write script -> smart contract? / validator script?
        - smart contract

        - script output -> an UTXO locked by validator script
        - UTXO -> an unspent transaction output(locked by pub key)
        - Extended UTXO -> locked by validator script
        - output produced by transactions, and are consumed by other transaction(spent)

    - seq:?

        1) create transaction
        2) create UTxO(for both spender and receiver) with our programmed validator script under
           receiver address
        3) create smart contract ?
        4) transaction spend the UTXOx(in which seq? spender or receiver first?)
        5) corresponding transaction create new UTXO
        6) spend
        7) depend on stake, chain need to decide when to put the transaction as new block



    -- how our api interact with plutus framework and plutus tx(on chain)?


    -- questions

    1) use whose public key to create UTOX?
    2) who sign the UTOX
    3) when to execute the transaction?


    -- note

    1) multiple pub pri signing : sign UTXO, sign transaction element(policy, payment)
