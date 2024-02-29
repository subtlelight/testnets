**`IBC Namada <> Osmosis`**

**Hermes memo_prefix:** **`subtlelight`**
```
## Chain: shielded-expedition.88f17d1d14
  - Client: 07-tendermint-1971
    * Connection: connection-965
      | State: OPEN
      | Counterparty state: OPEN
      + Channel: channel-573
        | Port: transfer
        | State: OPEN
        | Counterparty: channel-6023
Creation address: tnam1qq39pmztt3umjuyzyd8u7lg03ns8r5avpvld30va
```
```
# Chain: osmo-test-5
  - Client: 07-tendermint-2502
    * Connection: connection-2314
      | State: OPEN
      | Counterparty state: OPEN
      + Channel: channel-6023
        | Port: transfer
        | State: OPEN
        | Counterparty: channel-573
Creation address: osmo1s7k0twkkfxatehndu0uypqxgd835ezpus536g9
```

**`Test transactions:`**

**from shielded-expedition.88f17d1d14 to osmo-test-5**   
[https://www.mintscan.io/osmosis-testnet/tx/148B9C0B9D22B5856F6B8D660541FFCD25C3EF66C301AFB55EC044852959822C?height=5670415](https://www.mintscan.io/osmosis-testnet/tx/12939AC7D5173849C685D5BBF4B4B1332FF453FE59B5E448EC5C66236984D048?height=5684207)

**from osmo-test-5 to shielded-expedition.88f17d1d14**  
[https://www.mintscan.io/osmosis-testnet/tx/F1B79B70A97918B3B3F5CC4C93BB763D536D8658441F8863E9A5984A1C99B5F9?height=5670420](https://www.mintscan.io/osmosis-testnet/tx/26359AC7ABE00A386E77D1C29576F4CA32487913238CA3AAFA40A8315900D668?height=5684210)

**`Public RPC:`**

**shielded-expedition.88f17d1d14:** https://namosmoibc.subtlelight.space/

**osmo-test-5:** https://namosmoibc.subtlelight.space:1443/


**`create connection, channels output`**
```
SUCCESS Channel {
    ordering: Unordered,
    a_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "shielded-expedition.88f17d1d14",
                version: 0,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-1971",
        ),
        connection_id: ConnectionId(
            "connection-965",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-573",
            ),
        ),
        version: None,
    },
    b_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "osmo-test-5",
                version: 5,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-2502",
        ),
        connection_id: ConnectionId(
            "connection-2314",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-6023",
            ),
        ),
        version: None,
    },
    connection_delay: 0ns,
}
```
