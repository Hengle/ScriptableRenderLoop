# Unity Scriptable Render Loop testbed

**NOTE**: this is a testbed for a Unity feature that has not shipped yet! The project does not work with any public
Unity version, and things in it might and will be broken.

"Scriptable Render Loops" is a potential future Unity feature, think "Command Buffers, take two". We plan to ship the feature, and a
new modern built-in rendering loop with it. For now you can look around if you're _really_ curious, but like said above, this is
not useful for any public Unity version yet.

There's a more detailed overview document here: [ScriptableRenderLoop google doc](https://docs.google.com/document/d/1e2jkr_-v5iaZRuHdnMrSv978LuJKYZhsIYnrDkNAuvQ/edit?usp=sharing)

Did we mention it's a very WIP, no promises, may or might not ship feature, anything and everything in it can change? It totally is.


## For Unity 5.6 beta users

* Unity 5.6 beta 1 and beta 2 should use an older revision of this project, [tagged unity-5.6.0b1](../../releases/tag/unity-5.6.0b1) (commit `acc230b` on 2016 Nov 23). "BasicRenderLoopScene" scene is the basic example, with the scriptable render loop defaulting to off; enable it by enabling the component on the camera. All the other scenes may or might not work. Use of Windows/DX11 is preferred.
