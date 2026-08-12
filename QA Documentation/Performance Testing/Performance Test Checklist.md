# Performance Test Checklist

> Simulated portfolio checklist.

## Frame Rate
- [ ] Measure baseline FPS in a controlled scenario
- [ ] Measure during high-action scenes
- [ ] Measure during traversal/loading
- [ ] Check for sustained frame-time spikes

## Loading
- [ ] Cold launch time
- [ ] Level/area loading time
- [ ] Save/load time
- [ ] Fast travel or match transition time

## Stability
- [ ] Extended-session test
- [ ] Repeated loading cycles
- [ ] Repeated scene transitions
- [ ] Monitor crashes and hangs

## Memory / Resources
- [ ] Observe memory growth over time
- [ ] Check for abnormal resource accumulation
- [ ] Verify recovery after repeated scene transitions

## Mobile-specific
- [ ] Monitor temperature
- [ ] Check frame-rate stability under sustained load
- [ ] Check battery impact
- [ ] Test low-memory conditions where safely reproducible

## Reporting
Capture device/platform, build, graphics settings, duration, scenario, baseline and observed result.