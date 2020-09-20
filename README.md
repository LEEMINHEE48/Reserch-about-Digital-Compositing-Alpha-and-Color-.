# Reserch about Digital Compositing,Alpha and Color.

What is Digital Compositing ?
=============================

‘Compositing’ means ‘Add’
-------------------------
Just as it was mentioned, Compositing is add something, and Digitla Compositing is add something on film, animation,game ... ETC. 
For example, you are movie director, you want to present war that 10m soliders are at a war. 
Of cource, you can scout many extra actor, but you must pay so many cost. 
In such situations, you can solve the problem to use Digitial Compositing technology. 
You can express many people by modeling to use 3D Program or to use chroma – key technology. 

![unnamed](https://user-images.githubusercontent.com/70868719/93621900-2f1f6580-fa17-11ea-8b6c-97246d0e1ca9.jpg)

And you can compose movie by using compositing program looks natural by Lighting, Texturing, Rendering, color grading ... Etc 
It can on some program for example ) Nuke, 3D Maya, Photoshop, Blackmagic Fusion, After Effect… Etc

![blackmagic-fusion-interface](https://user-images.githubusercontent.com/70868719/93622702-8bcf5000-fa18-11ea-9ac8-2a450d527863.jpg)


**In modern film industry, Digitial Compositing technology is essential.** 

So now I represent about principles and tech about Digitial Compositing.
------------------------------------------------------------------------

-	**Chroma key compositing, or chroma keying** is a visual-effects and post-production technique for compositing (layering) two images or video streams together based on colour hues (chroma range)

![remove-green-screen-and-chroma-key-and-do-more png](https://user-images.githubusercontent.com/70868719/93623253-60993080-fa19-11ea-9d42-297a299cbf7e.jpeg)


-	**Rotoscoping** is started by technique that Animator copy film footage because of animation charicter’s realistic motion. Today, VFX artists are using Rotoscoping because of that delete wire, safety device, some unessential object….ETC. 
![do-frame-by-frame-rotoscoping](https://user-images.githubusercontent.com/70868719/93623291-79094b00-fa19-11ea-82b9-f24fbbf71856.jpg)

-	**Matte** painting and Digital Matte is the oldest VFX technique.
  
  It is a painted representation of a landscape, set or distant location that allows filmmakers to create the illusion of an environment that is not present at the filming location. Historically, matte painters and film technicians have used various techniques to combine a matte-painted image with live-action footage. At its best, depending on the skill levels of the artists and technicians, the effect is "seamless" and creates environments that would otherwise be impossible or expensive to film. In the scenes the painting part is static and movements are integrated on it.

![MattePainting-TajMahalDay](https://user-images.githubusercontent.com/70868719/93623387-9fc78180-fa19-11ea-814a-e2d3b6ec382a.jpg)

- **Color Correction & Grading**
   
   Color correction: Color correction is a process used in stage lighting, photography, television, cinematography, and other disciplines, which uses color gels, or filters, to alter the overall color of the light. Typically the light color is measured on a scale known as color temperature, as well as along a green–magenta axis orthogonal to the color temperature axis.
Without color correction gels, a scene may have a mix of various colors. Applying color correction gels in front of light sources can alter the color of the various light sources to match. Mixed lighting can produce an undesirable aesthetic when displayed on a television or in a theatre.
     
   
   Color grading: Color grading is the process of improving the appearance of an image for presentation in different environments on different devices. Various attributes of an image such as contrast, color, saturation, detail, black level, and white point may be enhanced whether for motion pictures, videos, or still images. Color grading and color correction are often used synonymously as terms for this process and can include the generation of artistic color effects through creative blending and compositing of different images. Color grading is generally now performed in a digital process either in a controlled environment such as a color suite, or in any location where a computer can be used in dim lighting.
   
![1c6996bbd101a9ed0e65cb709a85df06](https://user-images.githubusercontent.com/70868719/93623806-43189680-fa1a-11ea-9bc0-09033a7ae436.jpg)



**Above this, many techs are developed by VFX artist.** 

**Before that you study about VFX, you must know that Alpha and color.** 


Alpha Channel
=============

The alpha channel is a color component that represents the degree of transparency (or opacity) of a color (i.e., the red, green and blue channels). It is used to determine how a pixel is rendered when blended with another.

The alpha channel controls the transparency or opacity of a color. Its value can be represented as a real value, a percentage, or an integer: full transparency is 0.0, 0% or 0, whereas full opacity is 1.0, 100% or 255, respectively.

When a color (source) is blended with another color (background), e.g., when an image is overlaid onto another image, the alpha value of the source color is used to determine the resulting color. If the alpha value is opaque, the source color overwrites the destination color; if transparent, the source color is invisible, allowing the background color to show through. If the value is in between, the resulting color has a varying degree of transparency/opacity, which creates a translucent effect.

The alpha channel is used primarily in alpha blending and alpha compositing.

![1*Amydsx8D6qttFXbPRk9yWg](https://user-images.githubusercontent.com/70868719/93624387-3cd6ea00-fa1b-11ea-8b22-356852fc32ca.jpeg)

Color
=====
Color’s definition is light frequency that feel for color sence. 
It is essential element in film and Digital compositing. 
Exact color reproduction is the most important when we want to compose on digital unaffected.    
**For that to happen, we have to know that ‘Color’ on Digital Compositing.**

Gamut ( Gamma ) ----> Color space
---------------------------------
Color space is space that express color system on Three – dimensional

![1200px-CIE1931xy_gamut_comparison svg](https://user-images.githubusercontent.com/70868719/93624906-09488f80-fa1c-11ea-95ca-da2cd38c3915.png)


And If you want to know Color correction or grading process, you must know bleow concept.

**Hue** : Hue is one of the main properties (called color appearance parameters) of a color, defined technically (in the CIECAM02 model) as "the degree to which a stimulus can be described as similar to or different from stimuli that are described as red, orange, yellow, green, blue, purple"[1] (which in certain theories of color vision are called unique hues).

**Saturation** : Color saturation refers to the intensity of color in an image. As the saturation increases, the colors appear to be more pure. As the saturation decreases, the colors appear to be more washed-out or pale.

**Luminance** : Luminance is a photometric measure of the luminous intensity per unit area of light travelling in a given direction. It describes the amount of light that passes through, is emitted from, or is reflected from a particular area, and falls within a given solid angle.


![HSL_color_solid_dblcone](https://user-images.githubusercontent.com/70868719/93660221-6f1e3100-fa87-11ea-9e71-d14f8fb437f5.png)



RGB vs CMYK   
-----------
- **RGB(RED,  Green,  Blue)**  is additive color micture, so when you compose all color, it is more brighter. 
It is usually use when design digital frame. 

![RGB-color-model](https://user-images.githubusercontent.com/70868719/93625079-4c0a6780-fa1c-11ea-8360-6ee3333e3e67.jpg)


- **CMYK( Cyan, Magenta, Yellow, Key)** is subtractive micture, so when you compose all color, It is more darker. 
It is usually use when design print frame.

![R1280x0 fjpg](https://user-images.githubusercontent.com/70868719/93625044-3c8b1e80-fa1c-11ea-85a5-a3660e9faac9.jpeg)


**You can also utilize this concept when you purchase monitor.**
For Example) Adobe RGB VS SRGB

![sRGB-vs-Adobe-RGB-photo-example](https://user-images.githubusercontent.com/70868719/93625425-dfdc3380-fa1c-11ea-8322-4e801d3dce9c.jpg)


참고자료
-------

[Cg spectrum](https://www.cgspectrum.com/blog/what-is-compositing)

[Wikipeadia](https://en.wikipedia.org/wiki/Compositing)

[Wikipeadia](https://en.wikipedia.org/wiki/Color_space)

[Wikipeadia](https://en.wikipedia.org/wiki/Matte_painting)

[Inflearn] Davinci Resolve Lecture (Paid Service) 

[Techtopia](https://www.techopedia.com/definition/1945/alpha-channel)

[Techtopia](https://www.techopedia.com/definition/1945/alpha-channel)

[premium Beat](https://www.premiumbeat.com/blog/chroma-key-green-screen-guide/)

