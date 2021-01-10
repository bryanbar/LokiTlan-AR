# Open Source Augmented Reality pipeline

Pipline to allow for the use of a phone and an api to create a more immersive enviroment. This is done by creating 3d meshes that can then be refinded, or left as is, and allow for use with websites and augmented reality. The use cases are for retail to interactive documentation (DIY documentation)

Software:
  - Meshroom : processes images and creates various outputs that can be fed to blender or used as-is
  - Blender : refining of 3d models, meshes, so on
  - VirtualGL : allows for a graphics cards to be used as a single virtual card for containers or virtual machines
  - LookingGlass : allows for a graphics card to be passedthrough with a buffer copy
  - API : want to allow the ability to upload a video and return a finished output
  - KVM/QEMU : allows for the creation of virtual machines and use with virtualgl. Windows is too restrictive and so are vendors like Nvidia.
  - iPhone 11 camera : has a good camera and also has lidar which I might be useful for automating with photogrammetry
  - Drone camera : a small drone would allow for better angles
