# intel_lpmd_meteor_185H
## My Experiments with LPMD

Hi, I'm sharing my set of experiments as a public archive along with my thoughts on each.

[First good attempt](./first_good_enough.xml)  - This is my first working configuration, and it performs reasonably well. The main issue is that I'd like more aware HFI hints instead of utilization. Currently, it works more than necessary on E-cores instead of LP-cores without good reason. It also seems to get stuck on E-cores sometimes, which appears to be an escape from LPM.
