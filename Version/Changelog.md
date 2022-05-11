# SpaceDustUnbound

## 1.0.2

* Removed Blueshift harvesting/scanning compatibility as it now has innate SpaceDust integration. (Did not remove the Graviolium definitions)

## 1.0.1

* Fixed an issue that would break definitions if all included systems were not installed; now searches for installed GU systems before attempting to define resources.
* This unfortunately does not work if you only disable the system in GU_Settings; you must also remove the folder (this searches for direct file paths).
* Removed Liolan

## 1.0.0

* Support for multiple GU systems.
* This is made quick and dirty with no real balancing pass. I did try to make it with a shred of balance in mind, however. Tweak values as you see fit and consider
* even making a pull request with balance changes!
