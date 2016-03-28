# su-a-cyder
 
#########################______###############################__###################
########################/\##_##\#############################/\#\##################
###____##__##__#########\#\#\L\#\#############___###__##__###\_\#\#####__###_#__###
##/',__\/\#\/\#\##_______\#\##__#\##_______##/'___\/\#\/\#\##/'_`#\##/'__`\/\`'__\#
#/\__,#`\#\#\_\#\/\______\\#\#\/\#\/\______\/\#\__/\#\#\_\#\/\#\L\#\/\##__/\#\#\/##
#\/\____/\#\____/\/______/#\#\_\#\_\/______/\#\____\\/`____#\#\___,_\#\____\\#\_\##
##\/___/##\/___/############\/_/\/_/#########\/____/#`/___/>#\/__,_#/\/____/#\/_/##
########################################################/\___/#####################
########################################################\/__/############v0.9.2.1##

     su-A-cyder v0.9.2.1
     An Home-Brewed iOS Malware PoC Generator                
     Created by Chilik Tamir (@_coreDump) for BlackHatASIA 2016               

     It is heavily based on the great work done by the following (and many more):
         # Cydia & Theos tweaking system (@saurik & Dustin Howett)
         # libimobiledevice utilities (https://www.libimobiledevice.org)                
         # Bishop-fox, theos-jailed (https://github.com/BishopFox/theos-jailed)
         # Asger Hautop Drewsen,insert_dylib (https://github.com/Tyilo/insert_dylib)
         # Spaceship, an Apple development automation paltform (https://fastlane.tools/)


     LICENSE:
     su-A-cyder, Theos (and by extension, Logos) are available under the provisions of the GNU
     General Public License, version 3 (or later), available here:
     http://www.gnu.org/licenses/gpl-3.0.html.

     Projects created using Theos and/or Logos are not considered derivative works 
     (from a licensing standpoint, or, for that matter, any other standpoint) and
     are, as such, not required to be licensed under the GNU GPL.

     The included project templates are license-free. The use of a template does
     not confer a license to your project.


     DISCLAIMER: 
     This tool is an education tool for demonstration PoC of iOS Malware, Only!
     
     INSTALLATION: 
     1. Install ideviceinstaller from libimobile utilities (e.g. brew install ideviceinstaller)
     2. Install ideviceprovision from libimobile utilities (e.g. brew install ideviceprovision)
     3. git clone the modified fastlane fork from this repository and install it
     4. git clone the modified theos-jailed for from this reposiotory 
     5. create an apple home-brewed account and login to it with x-code (preferences, accounts)
     
     USAGE:
     1. Run the ./theos-jailed/bin/nic.pl and select su-a-cyder as a target
     2. Cd into the directory and modify the tweak as any other Theos tweak.
     3. Connect targeted device to USB
     4. Execute ./su-a-cyder.sh <path-to-decrypted-ipa-file-to-use-as-a-traget.ipa>
     5. Approve login credentails to Apple account
     6. After installation on device completed, approve app under the Preferences,Device-Managment iOS settings
     7. PoC is ready, use for demonstration only! 
  
