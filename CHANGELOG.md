<!-- markdownlint-disable MD041 -->
<p align="left"><img src="https://vulkan.lunarg.com/img/NewLunarGLogoBlack.png" alt="LunarG" width="263" height="113" /></p>
<p align="left">Copyright � 2015-2021 LunarG, Inc.</p>

[![Creative Commons][3]][4]

[3]: https://i.creativecommons.org/l/by-nd/4.0/88x31.png "Creative Commons License"
[4]: https://creativecommons.org/licenses/by-nd/4.0/

# Release notes

## [Vulkan Profiles Tools 1.3.XXX](https://github.com/LunarG/VulkanProfiles/tree/master) - February 2022

### Features:
- Add Vulkan capabilities exchange format schema
  - Add `VP_KHR_roadmap_2022.json` profile
  - Add `VP_LUNARG_desktop_portability_2022.json` profile
  - Add `VP_ANDROID_angle_es31.json` profile
  - Add `VP_ANDROID_baseline_2022.json` profile
- Add profile library to use profile in a Vulkan application code
  - Add API to check profile support by Vulkan devices
  - Add API to create VkDevice using a profile
  - Add APIs for profile reflection
- Add devsim2 layer to load profile
  - Add support of Vulkan 1.3 and all extensions
  - Add support of the Vulkan capabilities exchange format
