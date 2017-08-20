# Udacity Modern Apartment Project

This project is course 2 project of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

**Author** : Wayne Lee 
**Time for the Project** : about 10 hours

## Comment
### One thing I liked
I went to the unity asset store, searched for some nice and free Materials for the Apartment.

It was interesting to try and change different Materials, watching that how they reacted with various lights and other factors. 

### One thing that challenging me most
Deploy this project to my phone is really a callenge for me.

I got an Error when deploying the project at first, and I totally had no idea what caused it. I checked everything of my scripts , prefabs, game objects, then found nothing wrong with them.

Then I Googled it, someone said it was a bug of Unity Engine while deploying games to Android platform. I took his advise,  downloaded the "tools" file from the android offical website, unzip and overlayed the folder in my Android SDK folder. But still can not fix it. I thought there might be some students of udacity got the same problem with me, so went to the VRND forum for it.

Luckly I got this [post](https://discussions.udacity.com/t/help-unable-to-list-target-platforms-please-make-sure-the-adroid-sdk-path-is-correct-it-is/275627), and it said that I should use the specific version of the tools file.  I did as it suggested, And it worked for me too.

Yet bugs sometimes can be very depressing, I learned from this case is that problems can always be solved, but you have to keep your patience and effort.


## Versions
- Unity 5.5.1f1
- GVR Unity SDK v1.0.3

## Lighting Setting

### Baked GI
- Baked Resolution : 80 
- Baked Padding : 2
- Compressed : Uncheck
- Indirect Resolution : 2
- Ambient Occulusion : Uncheck
- Final Gather : Uncheck

### General GI
- Directional Mode : No-Directional
- Indirect Intensity : 1

### lights
- Point Light : 2
  - Shadow Type : Soft Shadows
    - Baked Shadow Radius : 1 (have tried 10, 5, 2, it appears that "1" makes the best shape of shadows )
- Area Light : 1

## Target Device
- Platform : Android
- Device Hardware
  - Phone model: Meizu Pro 5
  - SoC : Samsung Exynos 7420
  - RAM : 4GB LPDDR4
- **Stable FPS(with settings above) : 60**


