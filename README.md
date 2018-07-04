# Portal Painter

## Develop:

After [setting up and getting ARCore](https://developers.google.com/ar/develop/unity/getting-started), you will want to do the following:

* **Make your worlds.** Each world should be its own GameObject, and should have a child called `Center` located at whatever point you’d like the portal-camera to be. Whenever you spawn a portal, the `UIManager` will look for this `Center` object and place its camera there. (See the default `DemoWorld` object for an example.)

* **Add them to the UIManager GameObject.** They will be accessed in the `WorldTracker` script. You may add a custom skybox for a particular world there as well (make sure their indexes match).

* **Build and run.** Point your camera at your environment and wait until you see faint particles rise up from it. You can then use your finger to draw.

More granular instructions [here](https://github.com/googlecreativelab/arexperiments-portal-painter/issues/1#issuecomment-326012124).

## Debug commands:

* 2-finger tap to start painting with the next world (won’t change old portals)
* 3-finger tap to remove all portals on-screen

## Acknowledgements:

Built by [Jane Friedhoff](http://www.janefriedhoff.com) with friends on the Creative Lab team at Google. Sample model created by [Alex Jacobo-Blonder](http://ajacoboblonder.com/). Check out more at [AR Experiments](https://experiments.withgoogle.com/ar/) or read more about [ARCore](https://developers.google.com/ar).  
