# This device tree is for the Samsung Galaxy A54 5G variant A5460, which can be used in mainland China, Hong Kong, Macau and Taiwan. This device tree comes from @BlackMesa123 in the XDA forum. Thanks again for his contribution!

## Clone

```bash
git clone https://github.com/chingmiles/android_device_samsung_a54x.git -b main device/samsung/a54x
```

## Build

```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a54x-eng
mka recoveryimage
```

## Pre-Release
[Release](https://github.com/chingmiles/android_device_samsung_a54x/releases)


## Copyright

```
#
# Copyright (C) 2024 The TWRP Open Source Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
```
