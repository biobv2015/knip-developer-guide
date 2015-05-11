# BioBV Seminar 2015

## Getting started
1. Configure your KNIME Image Processing SDK according to the README file in the https://github.com/knime-ip/knip-sdk-setup repository. Selecting the ``knip-sdk-full`` target definiton is recommended.
2. Work through the tutorials and examples of ImgLib2 and ImageJ-Ops (see Tutorials and Examples)
3. Set-up your KNIME project and maven playground (Copy & Paste example projects from this repository)
4. Optional (required if you did not selected the `knip-sdk-full` target definition):  clone the following repositories from GitHub and import the java projects of these repositories into your Eclipse installation:
 - https://github.com/knime-ip/knip
 - https://github.com/knime-ip/knip-imagej2
5. For further reading on the eclipse plugin concept see:  https://tech.knime.org/overview-of-the-eclipse-plugin-concept.

## Frameworks and Tools
### ImgLib2:
- Short Description: ImgLib2 is a general-purpose, multidimensional image processing library.
- Link: http://imglib2.net
- GitHub: http://github.com/imglib/imglib2
- Tutorial "Getting Started": http://fiji.sc/ImgLib2_-_Introductory_Workshop
- Tutorial "Advanced": http://fiji.sc/ImgLib2_-_Advanced_Programming_Workshop

### ImageJ-Ops:
- Short Description: ImageJ OPS is an extensible Java framework for algorithms, particularly image processing algorithms.
- Uses: ImgLib2
- Link/GitHub: https://github.com/imagej/imagej-ops
- Tutorial "Using Ops": https://github.com/imagej/imagej-tutorials/tree/master/using-ops
- Tutorial "Creating Ops": https://github.com/imagej/imagej-tutorials/tree/master/create-a-new-op

### KNIME Image Processing:
- Short Description: KNIME Image Processing extends KNIME by providing integrations for the processing and analysis of huge amounts of image data.
- Uses: ImgLib2, ImageJ-Ops, ImageJ2
- Link: http://knime.imagej.net
- Webinar: https://www.youtube.com/watch?v=MqSIyqmm3EU&feature=youtu.be&a
- Example Workflows: https://tech.knime.org/community/image-processing#exampleworkflows
- Example Projects: https://github.com/knime-ip/knip-examples
- Lecture with KNIME Image Processing: https://github.com/kmader/Quantitative-Big-Imaging-2015/blob/master/Exercises/02-Description-KNIME.md

### ImageJ2 (optional for seminar):
- Short Description: ImageJ2 is a supercharged version of ImageJ1 with new features. ImageJ2 is an entirely redesigned, more powerful set of software libraries.
- Uses: ImgLib2, ImageJ-Ops
- Link: http://imagej.net
- GitHub: https://github.com/imagej
- Tutorials: https://github.com/imagej/imagej-tutorials

## Guidelines
- Questions/Bug-Reports concerning the individual frameworks: Issues in the corresponding repositories.
- Questions/Bug-Reports concerning KNIME Image Processing: http://tech.knime.org/forum/knime-image-processing

Asking questions in a public forum or reporting the bugs on github makes sure, that others also benefit from the answers to your questions or see which bugs have already been reported and maybe solved.
