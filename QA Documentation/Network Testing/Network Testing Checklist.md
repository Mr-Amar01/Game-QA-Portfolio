# Network Testing Checklist

> Simulated portfolio checklist.

## Connectivity
- [ ] Stable low-latency connection
- [ ] High latency
- [ ] Packet loss
- [ ] Temporary disconnect
- [ ] Full disconnect
- [ ] Reconnection

## Transitions
- [ ] Wi-Fi to mobile data
- [ ] Mobile data to Wi-Fi
- [ ] Network interruption during loading
- [ ] Network interruption during matchmaking
- [ ] Network interruption during active gameplay

## Recovery
- [ ] Client reconnects without restart
- [ ] Match state is synchronized
- [ ] HUD reflects authoritative state
- [ ] No duplicate actions occur after recovery
- [ ] Player receives appropriate connection feedback

## Multiplayer
- [ ] Matchmaking starts correctly
- [ ] Match entry succeeds
- [ ] Player joins/leaves correctly
- [ ] Results synchronize after match completion

## Reporting
Record network profile, latency/packet-loss conditions, build, platform, reproduction rate and recovery behavior.