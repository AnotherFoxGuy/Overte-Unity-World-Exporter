Unity to Overte Exporter
=======

It is a simple JSON and glTF writer designed to export static objects (and render skinned meshes to static poses) from Unity into the glTF format, preserving the materials, game object hierarchy and textures attached.

Features
-------------------------

1. Can export any GameObject into glTF format.
2. Exports will import into HiFi with one click of the menu


Known limitations
-------------------------

1. Parents which skew their children will not import correctly. This is a different from how HiFi versus Unity handles scaling.
2. The list of currently not supported items include partical effects, terrains, scripts, and cameras.

Tutorial
------------------------
It is very simple to use this exporter. You shouldn't have any problems, and if you do, please add an issue to the Github project

1. Import the github project files into your asset folder or bring in the Unity package
2. Select any GameObject in the scene or export the scene whole.
3. Go to the GameObjects menu and select Hifi glTF Exporter
4. Choose the folder to export to
5. There will be a prompt asking about the base URL to place on the JSON file.  If you are testing locally, choose do not use and this will export with local file references.  If you know the remote directly you are uploading to, then copy that root url and paste it here.
6. If you are using a remote directory, upload into it the folders created for the models/materials/textures.
7. Drop the JSON into Overte and you are good to go!