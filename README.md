# Lidl/Tuya Motion detection Device Handler
Smartthings Device handler for the Tuya Motion Sensor (rebranded in 
Europe as Lidl/silvercrest Motion Sensor).

     Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
     in compliance with the License. You may obtain a copy of the License at:
     
     http://www.apache.org/licenses/LICENSE-2.0
     
     Unless required by applicable law or agreed to in writing, software distributed under the License is distributed
     on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License
     for the specific language governing permissions and limitations under the License.


The Device Handler is an adaptation of the original Smartthings Motion 
Sensor code. It still contains a bit of unused code but it is mostly 
cleaned up. 

Note that it takes a minute or so for the device to become available after it
is added (it looks like it is offline while configuring).

After each triggering of the motion detector, it takes around 1 minute before it 
will be ready to detect again. This is not due to the device handler, but 
something built into the hardware to prevent it from using too much power.

## Installation
a) Go to https://graph.api.smartthings.com/ide/devices 

b) Click on My Device Handlers in the IDE's top menu

c) Hit the "+New Device Handler" at the top right corner

d) Hit the "From Code" tab on the left corner

e) Copy and paste the code from the device handler groovy file (from this repo)

e) Hit the create button at the bottom

f) Hit the "publish/for me" button at the top right corner (in the code window)

Enjoy! 
