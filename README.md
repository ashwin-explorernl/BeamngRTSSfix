# BeamngRTSSfix
fixes RTSS for Vulkan API v0.3.9.2

**requirements:**
BeamNG.drive 0.39.2.x
Vulkan renderer only
RTSS/MSI Afterburner users (maybe it helps with other apps that hook into beamng)
❌ Not meant for troubleshooting DirectX 12 issues

**verify Beamng.log beforehand for the following lines:**


19.49898|E|vulkan| (submit) Failed to submit to transfer queue [ErrorDeviceLost]  
19.49901|E|vulkan| No gpu markers  
19.49907|E|vulkan| Failed to submit to graphics queue [ErrorDeviceLost]   
19.49908|E|vulkan| GPU Markers: end [{ TopOfPipe }]  
19.49908|E|vulkan| GPU Markers: end [{ BottomOfPipe }]   


**enable DXGI chainswap presentation method in NV CPL:**
<img width="1799" height="74" alt="image" src="https://github.com/user-attachments/assets/9a41351b-5275-4a8a-9c52-94efcfe8611a" />

**SOURCE topic:**
https://www.reddit.com/r/BeamNG/comments/1vcvghu/rtss_and_vulkan_renderer_crash_fix/
