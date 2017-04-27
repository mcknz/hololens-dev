# Microsoft HoloLens development

This repo contains a Unity project (Unity 2017.1.0b2) that can be built and deployed to Microsoft HoloLens.

The project was created as part of the Pluralsight course [HoloLens Development Fundamentals][1].

Build settings are part of the Library directory, which the Unity docs recommend to [leave out of version control][2].

To configure a Unity build for HoloLens:

1. Go to File | Build Settings...
2. Add the "Main" Scene to the build
3. Select "Universal Windows Platform" as the platform, and set the options as follows:
    1. **Target Device**:     HoloLens
    2. **Build Type**:    D3D
    3. **SDK**:               Latest installed
    4. **Build and Run on**:  Local Machine
    5. **Unity C# Projects**: checked

4. Create an "App" directory in root, and select that folder for build


[1]: https://app.pluralsight.com/library/courses/hololens-development-fundamentals/
[2]: https://docs.unity3d.com/2017.1/Documentation/Manual/ExternalVersionControlSystemSupport.html

