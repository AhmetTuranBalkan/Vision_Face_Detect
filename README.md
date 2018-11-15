# VisionFaceDetect
Face Detection with IOS Vision Framework.

Vision and Core Machine Learning Framework:
Vision is a Framework that lets you apply high-performance image analysis and computer vision technology to images and videos, thus automatically identifying faces, detecting features and classifying scenes.CoreML framework predicts those images using trained or learning models.

You can find in Vision:

* Determine face rectangle and face landmarks i.e. eyes, brows, nose...
* Recognize and identify text,rectangular surface and barcode.
* Identify the horizon angle in an image
* Object tracking from Image and Video frames.

# Structure
Each of the features in the app follows the same structure. The image buffer(CVPixelBuffer) is captured and sent as input to Vision Request and then handled using Vision Handler and finally, the observations are computed and displayed as results.
