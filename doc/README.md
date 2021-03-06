# API Overview

Missing some function bindings? No problem! - <a href="https://github.com/justadudewhohacks/opencv4nodejs/#request-features"><b>Requesting new Features</b></a>

* <a href="./core/core.md"><b>core</b></a>
  * <a href="./core/core.md#partition">partition</a>
  * <a href="./core/core.md#kmeans">kmeans</a>
  * <a href="./core/Mat.md"><b>Mat</b></a>
    * <a href="./core/Mat.md#operators">operators</a>
      * <a href="./core/Mat.md#operators">add</a>
      * <a href="./core/Mat.md#operators">sub</a>
      * <a href="./core/Mat.md#operators">mul</a>
      * <a href="./core/Mat.md#operators">div</a>
      * <a href="./core/Mat.md#operators">hMul</a>
      * <a href="./core/Mat.md#operators">hDiv</a>
      * <a href="./core/Mat.md#operators">absdiff</a>
      * <a href="./core/Mat.md#operators">exp</a>
      * <a href="./core/Mat.md#operators">mean</a>
      * <a href="./core/Mat.md#operators">sqrt</a>
      * <a href="./core/Mat.md#operators">dot</a>
      * <a href="./core/Mat.md#operators">and</a>
      * <a href="./core/Mat.md#operators">or</a>
      * <a href="./core/Mat.md#operators">bitwiseAnd</a>
      * <a href="./core/Mat.md#operators">bitwiseOr</a>
      * <a href="./core/Mat.md#operators">bitwiseXor</a>
      * <a href="./core/Mat.md#operators">bitwiseNot</a>
      * <a href="./core/Mat.md#operators">abs</a>
      * <a href="./core/Mat.md#operators">determinant</a>
      * <a href="./core/Mat.md#operators">transpose</a>
    * <a href="./core/Mat.md#at">at</a>
    * <a href="./core/Mat.md#atRaw">atRaw</a>
    * <a href="./core/Mat.md#set">set</a>
    * <a href="./core/Mat.md#getData">getData</a>
    * <a href="./core/Mat.md#getDataAsync">getDataAsync</a>
    * <a href="./core/Mat.md#getDataAsArray">getDataAsArray</a>
    * <a href="./core/Mat.md#getRegion">getRegion</a>
    * <a href="./core/Mat.md#copy">copy</a>
    * <a href="./core/Mat.md#copyAsync">copyAsync</a>
    * <a href="./core/Mat.md#copyTo">copyTo</a>
    * <a href="./core/Mat.md#copyToAsync">copyToAsync</a>
    * <a href="./core/Mat.md#convertTo">convertTo</a>
    * <a href="./core/Mat.md#convertToAsync">convertToAsync</a>
    * <a href="./core/Mat.md#norm">norm</a>
    * <a href="./core/Mat.md#normalize">normalize</a>
    * <a href="./core/Mat.md#splitChannels">splitChannels</a>
    * <a href="./core/Mat.md#splitChannelsAsync">splitChannelsAsync</a>
    * <a href="./core/Mat.md#addWeighted">addWeighted</a>
    * <a href="./core/Mat.md#addWeightedAsync">addWeightedAsync</a>
    * <a href="./core/Mat.md#minMaxLoc">minMaxLoc</a>
    * <a href="./core/Mat.md#minMaxLocAsync">minMaxLocAsync</a>
    * <a href="./core/Mat.md#dct">dct</a>
    * <a href="./core/Mat.md#dctAsync">dctAsync</a>
    * <a href="./core/Mat.md#idct">idct</a>
    * <a href="./core/Mat.md#idctAsync">idctAsync</a>
    * <a href="./core/Mat.md#dft">dft</a>
    * <a href="./core/Mat.md#dftAsync">dftAsync</a>
    * <a href="./core/Mat.md#idft">idft</a>
    * <a href="./core/Mat.md#idftAsync">idftAsync</a>
    * <a href="./core/Mat.md#mulSpectrums">mulSpectrums</a>
    * <a href="./core/Mat.md#mulSpectrumsAsync">mulSpectrumsAsync</a>
    * <a href="./core/Mat.md#rescale">rescale</a>
    * <a href="./core/Mat.md#rescaleAsync">rescaleAsync</a>
    * <a href="./core/Mat.md#resize">resize</a>
    * <a href="./core/Mat.md#resizeAsync">resizeAsync</a>
    * <a href="./core/Mat.md#resizeToMax">resizeToMax</a>
    * <a href="./core/Mat.md#resizeToMaxAsync">resizeToMaxAsync</a>
    * <a href="./core/Mat.md#threshold">threshold</a>
    * <a href="./core/Mat.md#thresholdAsync">thresholdAsync</a>
    * <a href="./core/Mat.md#adaptiveThreshold">adaptiveThreshold</a>
    * <a href="./core/Mat.md#adaptiveThresholdAsync">adaptiveThresholdAsync</a>
    * <a href="./core/Mat.md#inRange">inRange</a>
    * <a href="./core/Mat.md#inRangeAsync">inRangeAsync</a>
    * <a href="./core/Mat.md#cvtColor">cvtColor</a>
    * <a href="./core/Mat.md#cvtColorAsync">cvtColorAsync</a>
    * <a href="./core/Mat.md#bgrToGray">bgrToGray</a>
    * <a href="./core/Mat.md#bgrToGrayAsync">bgrToGrayAsync</a>
    * <a href="./core/Mat.md#warpAffine">warpAffine</a>
    * <a href="./core/Mat.md#warpAffineAsync">warpAffineAsync</a>
    * <a href="./core/Mat.md#warpPerspective">warpPerspective</a>
    * <a href="./core/Mat.md#warpPerspectiveAsync">warpPerspectiveAsync</a>
    * <a href="./core/Mat.md#dilate">dilate</a>
    * <a href="./core/Mat.md#dilateAsync">dilateAsync</a>
    * <a href="./core/Mat.md#erode">erode</a>
    * <a href="./core/Mat.md#erodeAsync">erodeAsync</a>
    * <a href="./core/Mat.md#morphologyEx">morphologyEx</a>
    * <a href="./core/Mat.md#morphologyExAsync">morphologyExAsync</a>
    * <a href="./core/Mat.md#distanceTransform">distanceTransform</a>
    * <a href="./core/Mat.md#distanceTransformAsync">distanceTransformAsync</a>
    * <a href="./core/Mat.md#distanceTransformWithLabels">distanceTransformWithLabels</a>
    * <a href="./core/Mat.md#distanceTransformWithLabelsAsync">distanceTransformWithLabelsAsync</a>
    * <a href="./core/Mat.md#grabCut">grabCut</a>
    * <a href="./core/Mat.md#grabCutAsync">grabCutAsync</a>
    * <a href="./core/Mat.md#blur">blur</a>
    * <a href="./core/Mat.md#blurAsync">blurAsync</a>
    * <a href="./core/Mat.md#gaussianBlur">gaussianBlur</a>
    * <a href="./core/Mat.md#gaussianBlurAsync">gaussianBlurAsync</a>
    * <a href="./core/Mat.md#medianBlur">medianBlur</a>
    * <a href="./core/Mat.md#medianBlurAsync">medianBlurAsync</a>
    * <a href="./core/Mat.md#connectedComponents">connectedComponents</a>
    * <a href="./core/Mat.md#connectedComponentsAsync">connectedComponentsAsync</a>
    * <a href="./core/Mat.md#connectedComponentsWithStats">connectedComponentsWithStats</a>
    * <a href="./core/Mat.md#connectedComponentsWithStatsAsync">connectedComponentsWithStatsAsync</a>
    * <a href="./core/Mat.md#findContours">findContours</a>
    * <a href="./core/Mat.md#findContoursAsync">findContoursAsync</a>
    * <a href="./core/Mat.md#moments">moments</a>
    * <a href="./core/Mat.md#momentsAsync">momentsAsync</a>
    * <a href="./core/Mat.md#drawContours">drawContours</a>
    * <a href="./core/Mat.md#drawLine">drawLine</a>
    * <a href="./core/Mat.md#drawCircle">drawCircle</a>
    * <a href="./core/Mat.md#drawRectangle">drawRectangle</a>
    * <a href="./core/Mat.md#drawEllipse">drawEllipse</a>
    * <a href="./core/Mat.md#putText">putText</a>
    * <a href="./core/Mat.md#matchTemplate">matchTemplate</a>
    * <a href="./core/Mat.md#matchTemplateAsync">matchTemplateAsync</a>
    * <a href="./core/Mat.md#canny">canny</a>
    * <a href="./core/Mat.md#cannyAsync">cannyAsync</a>
    * <a href="./core/Mat.md#sobel">sobel</a>
    * <a href="./core/Mat.md#sobelAsync">sobelAsync</a>
    * <a href="./core/Mat.md#scharr">scharr</a>
    * <a href="./core/Mat.md#scharrAsync">scharrAsync</a>
    * <a href="./core/Mat.md#laplacian">laplacian</a>
    * <a href="./core/Mat.md#laplacianAsync">laplacianAsync</a>
    * <a href="./core/Mat.md#pyrDown">pyrDown</a>
    * <a href="./core/Mat.md#pyrDownAsync">pyrDownAsync</a>
    * <a href="./core/Mat.md#pyrUp">pyrUp</a>
    * <a href="./core/Mat.md#pyrUpAsync">pyrUpAsync</a>
    * <a href="./core/Mat.md#buildPyramid">buildPyramid</a>
    * <a href="./core/Mat.md#buildPyramidAsync">buildPyramidAsync</a>
    * <a href="./core/Mat.md#houghLines">houghLines</a>
    * <a href="./core/Mat.md#houghLinesAsync">houghLinesAsync</a>
    * <a href="./core/Mat.md#houghLinesP">houghLinesP</a>
    * <a href="./core/Mat.md#houghLinesPAsync">houghLinesPAsync</a>
    * <a href="./core/Mat.md#houghCircles">houghCircles</a>
    * <a href="./core/Mat.md#houghCirclesAsync">houghCirclesAsync</a>
    * <a href="./core/Mat.md#rodrigues">rodrigues</a>
    * <a href="./core/Mat.md#rodriguesAsync">rodriguesAsync</a>
    * <a href="./core/Mat.md#rqDecomp3x3">rqDecomp3x3</a>
    * <a href="./core/Mat.md#rqDecomp3x3Async">rqDecomp3x3Async</a>
    * <a href="./core/Mat.md#decomposeProjectionMatrix">decomposeProjectionMatrix</a>
    * <a href="./core/Mat.md#decomposeProjectionMatrixAsync">decomposeProjectionMatrixAsync</a>
    * <a href="./core/Mat.md#matMulDeriv">matMulDeriv</a>
    * <a href="./core/Mat.md#matMulDerivAsync">matMulDerivAsync</a>
    * <a href="./core/Mat.md#findChessboardCorners">findChessboardCorners</a>
    * <a href="./core/Mat.md#findChessboardCornersAsync">findChessboardCornersAsync</a>
    * <a href="./core/Mat.md#drawChessboardCorners">drawChessboardCorners</a>
    * <a href="./core/Mat.md#drawChessboardCornersAsync">drawChessboardCornersAsync</a>
    * <a href="./core/Mat.md#find4QuadCornerSubpix">find4QuadCornerSubpix</a>
    * <a href="./core/Mat.md#find4QuadCornerSubpixAsync">find4QuadCornerSubpixAsync</a>
    * <a href="./core/Mat.md#calibrationMatrixValues">calibrationMatrixValues</a>
    * <a href="./core/Mat.md#calibrationMatrixValuesAsync">calibrationMatrixValuesAsync</a>
    * <a href="./core/Mat.md#stereoRectify">stereoRectify</a>
    * <a href="./core/Mat.md#stereoRectifyAsync">stereoRectifyAsync</a>
    * <a href="./core/Mat.md#rectify3Collinear">rectify3Collinear</a>
    * <a href="./core/Mat.md#rectify3CollinearAsync">rectify3CollinearAsync</a>
    * <a href="./core/Mat.md#getOptimalNewCameraMatrix">getOptimalNewCameraMatrix</a>
    * <a href="./core/Mat.md#getOptimalNewCameraMatrixAsync">getOptimalNewCameraMatrixAsync</a>
    * <a href="./core/Mat.md#decomposeEssentialMat">decomposeEssentialMat</a>
    * <a href="./core/Mat.md#decomposeEssentialMatAsync">decomposeEssentialMatAsync</a>
    * <a href="./core/Mat.md#triangulatePoints">triangulatePoints</a>
    * <a href="./core/Mat.md#triangulatePointsAsync">triangulatePointsAsync</a>
    * <a href="./core/Mat.md#correctMatches">correctMatches</a>
    * <a href="./core/Mat.md#correctMatchesAsync">correctMatchesAsync</a>
    * <a href="./core/Mat.md#filterSpeckles">filterSpeckles</a>
    * <a href="./core/Mat.md#filterSpecklesAsync">filterSpecklesAsync</a>
    * <a href="./core/Mat.md#validateDisparity">validateDisparity</a>
    * <a href="./core/Mat.md#validateDisparityAsync">validateDisparityAsync</a>
    * <a href="./core/Mat.md#reprojectImageTo3D">reprojectImageTo3D</a>
    * <a href="./core/Mat.md#reprojectImageTo3DAsync">reprojectImageTo3DAsync</a>
    * <a href="./core/Mat.md#decomposeHomographyMat">decomposeHomographyMat</a>
    * <a href="./core/Mat.md#decomposeHomographyMatAsync">decomposeHomographyMatAsync</a>
    * <a href="./core/Mat.md#findEssentialMat">findEssentialMat</a>
    * <a href="./core/Mat.md#findEssentialMatAsync">findEssentialMatAsync</a>
    * <a href="./core/Mat.md#recoverPose">recoverPose</a>
    * <a href="./core/Mat.md#recoverPoseAsync">recoverPoseAsync</a>
  * <a href="./core/Vec.md"><b>Vec</b></a>
    * <a href="./core/Vec.md#operators">operators</a>
      * <a href="./core/Vec.md#operators">add</a>
      * <a href="./core/Vec.md#operators">sub</a>
      * <a href="./core/Vec.md#operators">mul</a>
      * <a href="./core/Vec.md#operators">div</a>
      * <a href="./core/Vec.md#operators">hMul</a>
      * <a href="./core/Vec.md#operators">hDiv</a>
      * <a href="./core/Vec.md#operators">absdiff</a>
      * <a href="./core/Vec.md#operators">exp</a>
      * <a href="./core/Vec.md#operators">mean</a>
      * <a href="./core/Vec.md#operators">sqrt</a>
      * <a href="./core/Vec.md#operators">norm</a>
      * <a href="./core/Vec.md#operators">cross</a>
    * <a href="./core/Vec.md#at">at</a>
  * <a href="./core/Point.md"><b>Point</b></a>
    * <a href="./core/Point.md#operators">operators</a>
      * <a href="./core/Point.md#operators">add</a>
      * <a href="./core/Point.md#operators">sub</a>
      * <a href="./core/Point.md#operators">mul</a>
      * <a href="./core/Point.md#operators">div</a>
      * <a href="./core/Point.md#operators">norm</a>
    * <a href="./core/Point.md#at">at</a>
  * <a href="./core/Size.md"><b>Size</b></a>
  * <a href="./core/Rect.md"><b>Rect</b></a>
  * <a href="./core/RotatedRect.md"><b>RotatedRect</b></a>
    * <a href="./core/RotatedRect.md#boundingRect">boundingRect</a>
  * <a href="./core/TermCriteria.md"><b>TermCriteria</b></a>
* <a href="./io/io.md"><b>io</b></a>
  * <a href="./io/io.md#imread">imread</a>
  * <a href="./io/io.md#imreadAsync">imreadAsync</a>
  * <a href="./io/io.md#imwrite">imwrite</a>
  * <a href="./io/io.md#imwriteAsync">imwriteAsync</a>
  * <a href="./io/io.md#imshow">imshow</a>
  * <a href="./io/io.md#imshowWait">imshowWait</a>
  * <a href="./io/io.md#waitKey">waitKey</a>
  * <a href="./io/io.md#imencode">imencode</a>
  * <a href="./io/io.md#imencodeAsync">imencodeAsync</a>
  * <a href="./io/io.md#imdecode">imdecode</a>
  * <a href="./io/io.md#imdecodeAsync">imdecodeAsync</a>
  * <a href="./io/VideoCapture.md"><b>VideoCapture</b></a>
    * <a href="./io/VideoCapture.md#read">read</a>
    * <a href="./io/VideoCapture.md#readAsync">readAsync</a>
    * <a href="./io/VideoCapture.md#reset">reset</a>
    * <a href="./io/VideoCapture.md#get">get</a>
    * <a href="./io/VideoCapture.md#set">set</a>
    * <a href="./io/VideoCapture.md#release">release</a>
  * <a href="./io/VideoWriter.md"><b>VideoWriter</b></a>
    * <a href="./io/VideoWriter.md#fourcc">fourcc</a>
    * <a href="./io/VideoWriter.md#write">write</a>
    * <a href="./io/VideoWriter.md#writeAsync">writeAsync</a>
    * <a href="./io/VideoWriter.md#get">get</a>
    * <a href="./io/VideoWriter.md#set">set</a>
    * <a href="./io/VideoWriter.md#release">release</a>
* <a href="./imgproc/imgproc.md"><b>imgproc</b></a>
  * <a href="./imgproc/imgproc.md#getStructuringElement">getStructuringElement</a>
  * <a href="./imgproc/imgproc.md#getRotationMatrix2D">getRotationMatrix2D</a>
  * <a href="./imgproc/imgproc.md#getAffineTransform">getAffineTransform</a>
  * <a href="./imgproc/imgproc.md#getPerspectiveTransform">getPerspectiveTransform</a>
  * <a href="./imgproc/imgproc.md#calcHist">calcHist</a>
  * <a href="./imgproc/imgproc.md#plot1DHist">plot1DHist</a>
  * <a href="./imgproc/imgproc.md#fitLine">fitLine</a>
  * <a href="./imgproc/imgproc.md#canny">canny</a>
  * <a href="./imgproc/Moments.md"><b>Moments</b></a>
    * <a href="./imgproc/Moments.md#huMoments">huMoments</a>
  * <a href="./imgproc/Contour.md"><b>Contour</b></a>
    * <a href="./imgproc/Contour.md#getPoints">getPoints</a>
    * <a href="./imgproc/Contour.md#arcLength">arcLength</a>
    * <a href="./imgproc/Contour.md#convexHull">convexHull</a>
    * <a href="./imgproc/Contour.md#convexityDefects">convexityDefects</a>
    * <a href="./imgproc/Contour.md#boundingRect">boundingRect</a>
    * <a href="./imgproc/Contour.md#minEnclosingCircle">minEnclosingCircle</a>
    * <a href="./imgproc/Contour.md#minEnclosingTriangle">minEnclosingTriangle</a>
    * <a href="./imgproc/Contour.md#minAreaRect">minAreaRect</a>
    * <a href="./imgproc/Contour.md#fitEllipse">fitEllipse</a>
    * <a href="./imgproc/Contour.md#approxPolyDP">approxPolyDP</a>
    * <a href="./imgproc/Contour.md#pointPolygonTest">pointPolygonTest</a>
    * <a href="./imgproc/Contour.md#matchShapes">matchShapes</a>
    * <a href="./imgproc/Contour.md#moments">moments</a>
* <a href="./ximgproc/ximgproc.md"><b>ximgproc</b></a>
  * <a href="./ximgproc/SuperpixelSEEDS.md"><b>SuperpixelSEEDS</b></a>
    * <a href="./ximgproc/SuperpixelSEEDS.md#iterate">iterate</a>
  * <a href="./ximgproc/SuperpixelSLIC.md"><b>SuperpixelSLIC</b></a>
    * <a href="./ximgproc/SuperpixelSLIC.md#iterate">iterate</a>
  * <a href="./ximgproc/SuperpixelLSC.md"><b>SuperpixelLSC</b></a>
    * <a href="./ximgproc/SuperpixelLSC.md#iterate">iterate</a>
* <a href="./objdetect/objdetect.md"><b>objdetect</b></a>
  * <a href="./objdetect/CascadeClassifier.md"><b>CascadeClassifier</b></a>
    * <a href="./objdetect/CascadeClassifier.md#detectMultiScale">detectMultiScale</a>
    * <a href="./objdetect/CascadeClassifier.md#detectMultiScaleAsync">detectMultiScaleAsync</a>
    * <a href="./objdetect/CascadeClassifier.md#detectMultiScaleWithRejectLevels">detectMultiScaleWithRejectLevels</a>
    * <a href="./objdetect/CascadeClassifier.md#detectMultiScaleWithRejectLevelsAsync">detectMultiScaleWithRejectLevelsAsync</a>
  * <a href="./objdetect/HOGDescriptor.md"><b>HOGDescriptor</b></a>
    * <a href="./objdetect/HOGDescriptor.md#.getDaimlerPeopleDetector">getDaimlerPeopleDetector</a>
    * <a href="./objdetect/HOGDescriptor.md#.getDefaultPeopleDetector">getDefaultPeopleDetector</a>
    * <a href="./objdetect/HOGDescriptor.md#.compute">compute</a>
    * <a href="./objdetect/HOGDescriptor.md#.computeAsync">computeAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.computeGradient">computeGradient</a>
    * <a href="./objdetect/HOGDescriptor.md#.computeGradientAsync">computeGradientAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.detect">detect</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectAsync">detectAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectROI">detectROI</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectROIAsync">detectROIAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectMultiScale">detectMultiScale</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectMultiScaleAsync">detectMultiScaleAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectMultiScaleROI">detectMultiScaleROI</a>
    * <a href="./objdetect/HOGDescriptor.md#.detectMultiScaleROIAsync">detectMultiScaleROIAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.groupRectangles">groupRectangles</a>
    * <a href="./objdetect/HOGDescriptor.md#.groupRectanglesAsync">groupRectanglesAsync</a>
    * <a href="./objdetect/HOGDescriptor.md#.checkDetectorSize">checkDetectorSize</a>
    * <a href="./objdetect/HOGDescriptor.md#.setSVMDetector">setSVMDetector</a>
    * <a href="./objdetect/HOGDescriptor.md#.save">save</a>
    * <a href="./objdetect/HOGDescriptor.md#.load">load</a>
  * <a href="./objdetect/DetectionROI.md"><b>DetectionROI</b></a>
* <a href="./machinelearning/machinelearning.md"><b>machinelearning</b></a>
  * <a href="./machinelearning/ParamGrid.md"><b>ParamGrid</b></a>
  * <a href="./machinelearning/TrainData.md"><b>TrainData</b></a>
  * <a href="./machinelearning/SVM.md"><b>SVM</b></a>
    * <a href="./machinelearning/SVM.md#setParams">setParams</a>
    * <a href="./machinelearning/SVM.md#train">train</a>
    * <a href="./machinelearning/SVM.md#trainAsync">trainAsync</a>
    * <a href="./machinelearning/SVM.md#trainAuto">trainAuto</a>
    * <a href="./machinelearning/SVM.md#trainAutoAsync">trainAutoAsync</a>
    * <a href="./machinelearning/SVM.md#predict">predict</a>
    * <a href="./machinelearning/SVM.md#save">save</a>
    * <a href="./machinelearning/SVM.md#load">load</a>
    * <a href="./machinelearning/SVM.md#getSupportVectors">getSupportVectors</a>
    * <a href="./machinelearning/SVM.md#calcError">calcError</a>
* <a href="./dnn/dnn.md"><b>dnn</b></a>
  * <a href="./dnn/Net.md"><b>Net</b></a>
    * <a href="./dnn/Net.md#setInput">setInput</a>
    * <a href="./dnn/Net.md#setInputAsync">setInputAsync</a>
    * <a href="./dnn/Net.md#forward">forward</a>
    * <a href="./dnn/Net.md#forwardAsync">forwardAsync</a>
  * <a href="./dnn/dnn.md#readNetFromTensorflow">readNetFromTensorflow</a>
  * <a href="./dnn/dnn.md#readNetFromTensorflowAsync">readNetFromTensorflowAsync</a>
  * <a href="./dnn/dnn.md#blobFromImage">blobFromImage</a>
  * <a href="./dnn/dnn.md#blobFromImageAsync">blobFromImageAsync</a>
  * <a href="./dnn/dnn.md#blobFromImages">blobFromImages</a>
  * <a href="./dnn/dnn.md#blobFromImagesAsync">blobFromImagesAsync</a>
* <a href="./video/video.md"><b>video</b></a>
  * <a href="./video/BackgroundSubtractorMOG2.md"><b>BackgroundSubtractorMOG2</b></a>
    * <a href="./video/BackgroundSubtractorMOG2.md#apply">apply</a>
  * <a href="./video/BackgroundSubtractorKNN.md"><b>BackgroundSubtractorKNN</b></a>
    * <a href="./video/BackgroundSubtractorKNN.md#apply">apply</a>
* <a href="./calib3d.md"><b>calib3d</b></a>
  * <a href="./calib3d.md#findHomography">findHomography</a>
  * <a href="./calib3d.md#composeRT">composeRT</a>
  * <a href="./calib3d.md#composeRTAsync">composeRTAsync</a>
  * <a href="./calib3d.md#solvePnP">solvePnP</a>
  * <a href="./calib3d.md#solvePnPAsync">solvePnPAsync</a>
  * <a href="./calib3d.md#solvePnPRansac">solvePnPRansac</a>
  * <a href="./calib3d.md#solvePnPRansacAsync">solvePnPRansacAsync</a>
  * <a href="./calib3d.md#projectPoints">projectPoints</a>
  * <a href="./calib3d.md#projectPointsAsync">projectPointsAsync</a>
  * <a href="./calib3d.md#initCameraMatrix2D">initCameraMatrix2D</a>
  * <a href="./calib3d.md#initCameraMatrix2DAsync">initCameraMatrix2DAsync</a>
  * <a href="./calib3d.md#calibrateCamera">calibrateCamera</a>
  * <a href="./calib3d.md#calibrateCameraAsync">calibrateCameraAsync</a>
  * <a href="./calib3d.md#stereoCalibrate">stereoCalibrate</a>
  * <a href="./calib3d.md#stereoCalibrateAsync">stereoCalibrateAsync</a>
  * <a href="./calib3d.md#stereoRectifyUncalibrated">stereoRectifyUncalibrated</a>
  * <a href="./calib3d.md#stereoRectifyUncalibratedAsync">stereoRectifyUncalibratedAsync</a>
  * <a href="./calib3d.md#findFundamentalMat">findFundamentalMat</a>
  * <a href="./calib3d.md#findFundamentalMatAsync">findFundamentalMatAsync</a>
  * <a href="./calib3d.md#findEssentialMat">findEssentialMat</a>
  * <a href="./calib3d.md#findEssentialMatAsync">findEssentialMatAsync</a>
  * <a href="./calib3d.md#recoverPose">recoverPose</a>
  * <a href="./calib3d.md#recoverPoseAsync">recoverPoseAsync</a>
  * <a href="./calib3d.md#computeCorrespondEpilines">computeCorrespondEpilines</a>
  * <a href="./calib3d.md#computeCorrespondEpilinesAsync">computeCorrespondEpilinesAsync</a>
  * <a href="./calib3d.md#getValidDisparityROI">getValidDisparityROI</a>
  * <a href="./calib3d.md#getValidDisparityROIAsync">getValidDisparityROIAsync</a>
  * <a href="./calib3d.md#estimateAffine3D">estimateAffine3D</a>
  * <a href="./calib3d.md#estimateAffine3DAsync">estimateAffine3DAsync</a>
  * <a href="./calib3d.md#sampsonDistance">sampsonDistance</a>
  * <a href="./calib3d.md#sampsonDistanceAsync">sampsonDistanceAsync</a>
  * <a href="./calib3d.md#calibrateCameraExtended">calibrateCameraExtended</a>
  * <a href="./calib3d.md#calibrateCameraExtendedAsync">calibrateCameraExtendedAsync</a>
  * <a href="./calib3d.md#estimateAffine2D">estimateAffine2D</a>
  * <a href="./calib3d.md#estimateAffine2DAsync">estimateAffine2DAsync</a>
  * <a href="./calib3d.md#estimateAffinePartial2D">estimateAffinePartial2D</a>
  * <a href="./calib3d.md#estimateAffinePartial2DAsync">estimateAffinePartial2DAsync</a>
  * <a href="./calib3d.md#solveP3P">solveP3P</a>
  * <a href="./calib3d.md#solveP3PAsync">solveP3PAsync</a>
* <a href="./photo.md"><b>photo</b></a>
  * <a href="./photo.md#fastNlMeansDenoisingColored">fastNlMeansDenoisingColored</a>
* <a href="./features2d/features2d.md"><b>features2d</b></a>
  * <a href="./features2d/features2d.md#matchFlannBased">matchFlannBased</a>
  * <a href="./features2d/features2d.md#matchFlannBasedAsync">matchFlannBasedAsync</a>
  * <a href="./features2d/features2d.md#matchBruteForce">matchBruteForce</a>
  * <a href="./features2d/features2d.md#matchBruteForceAsync">matchBruteForceAsync</a>
  * <a href="./features2d/features2d.md#matchBruteForceL1">matchBruteForceL1</a>
  * <a href="./features2d/features2d.md#matchBruteForceL1Async">matchBruteForceL1Async</a>
  * <a href="./features2d/features2d.md#matchBruteForceHamming">matchBruteForceHamming</a>
  * <a href="./features2d/features2d.md#matchBruteForceHammingAsync">matchBruteForceHammingAsync</a>
  * <a href="./features2d/features2d.md#matchBruteForceHammingLut">matchBruteForceHammingLut</a>
  * <a href="./features2d/features2d.md#matchBruteForceHammingLutAsync">matchBruteForceHammingLutAsync</a>
  * <a href="./features2d/features2d.md#matchBruteForceSL2">matchBruteForceSL2</a>
  * <a href="./features2d/features2d.md#matchBruteForceSL2Async">matchBruteForceSL2Async</a>
  * <a href="./features2d/features2d.md#drawKeyPoints">drawKeyPoints</a>
  * <a href="./features2d/features2d.md#drawMatches">drawMatches</a>
  * <a href="./features2d/KeyPoint.md"><b>KeyPoint</b></a>
  * <a href="./features2d/DescriptorMatch.md"><b>DescriptorMatch</b></a>
  * <a href="./features2d/AGASTDetector.md"><b>AGASTDetector</b></a>
    * <a href="./features2d/AGASTDetector.md#detect">detect</a>
    * <a href="./features2d/AGASTDetector.md#detectAsync">detectAsync</a>
  * <a href="./features2d/AKAZEDetector.md"><b>AKAZEDetector</b></a>
    * <a href="./features2d/AKAZEDetector.md#detect">detect</a>
    * <a href="./features2d/AKAZEDetector.md#detectAsync">detectAsync</a>
    * <a href="./features2d/AKAZEDetector.md#compute">compute</a>
    * <a href="./features2d/AKAZEDetector.md#computeAsync">computeAsync</a>
  * <a href="./features2d/BRISKDetector.md"><b>BRISKDetector</b></a>
    * <a href="./features2d/BRISKDetector.md#detect">detect</a>
    * <a href="./features2d/BRISKDetector.md#detectAsync">detectAsync</a>
    * <a href="./features2d/BRISKDetector.md#compute">compute</a>
    * <a href="./features2d/BRISKDetector.md#computeAsync">computeAsync</a>
  * <a href="./features2d/FASTDetector.md"><b>FASTDetector</b></a>
    * <a href="./features2d/FASTDetector.md#detect">detect</a>
    * <a href="./features2d/FASTDetector.md#detectAsync">detectAsync</a>
  * <a href="./features2d/KAZEDetector.md"><b>KAZEDetector</b></a>
    * <a href="./features2d/KAZEDetector.md#detect">detect</a>
    * <a href="./features2d/KAZEDetector.md#detectAsync">detectAsync</a>
    * <a href="./features2d/KAZEDetector.md#compute">compute</a>
    * <a href="./features2d/KAZEDetector.md#computeAsync">computeAsync</a>
  * <a href="./features2d/GFTTDetector.md"><b>GFTTDetector</b></a>
    * <a href="./features2d/GFTTDetector.md#detect">detect</a>
    * <a href="./features2d/GFTTDetector.md#detectAsync">detectAsync</a>
  * <a href="./features2d/MSERDetector.md"><b>MSERDetector</b></a>
    * <a href="./features2d/MSERDetector.md#detect">detect</a>
    * <a href="./features2d/MSERDetector.md#detectAsync">detectAsync</a>
  * <a href="./features2d/ORBDetector.md"><b>ORBDetector</b></a>
    * <a href="./features2d/ORBDetector.md#detect">detect</a>
    * <a href="./features2d/ORBDetector.md#detectAsync">detectAsync</a>
    * <a href="./features2d/ORBDetector.md#compute">compute</a>
    * <a href="./features2d/ORBDetector.md#computeAsync">computeAsync</a>
  * <a href="./features2d/SimpleBlobDetectorParams.md"><b>SimpleBlobDetectorParams</b></a>
  * <a href="./features2d/SimpleBlobDetector.md"><b>SimpleBlobDetector</b></a>
    * <a href="./features2d/SimpleBlobDetector.md#detect">detect</a>
    * <a href="./features2d/SimpleBlobDetector.md#detectAsync">detectAsync</a>
    * <a href="./features2d/SimpleBlobDetector.md#compute">compute</a>
    * <a href="./features2d/SimpleBlobDetector.md#computeAsync">computeAsync</a>
* <a href="./xfeatures2d/xfeatures2d.md"><b>xfeatures2d</b></a>
  * <a href="./xfeatures2d/SIFTDetector.md"><b>SIFTDetector</b></a>
    * <a href="./xfeatures2d/SIFTDetector.md#detect">detect</a>
    * <a href="./xfeatures2d/SIFTDetector.md#detectAsync">detectAsync</a>
    * <a href="./xfeatures2d/SIFTDetector.md#compute">compute</a>
    * <a href="./xfeatures2d/SIFTDetector.md#computeAsync">computeAsync</a>
  * <a href="./xfeatures2d/SURFDetector.md"><b>SURFDetector</b></a>
    * <a href="./xfeatures2d/SURFDetector.md#detect">detect</a>
    * <a href="./xfeatures2d/SURFDetector.md#detectAsync">detectAsync</a>
    * <a href="./xfeatures2d/SURFDetector.md#compute">compute</a>
    * <a href="./xfeatures2d/SURFDetector.md#computeAsync">computeAsync</a>
* <a href="./tracking/tracking.md"><b>tracking</b></a>
  * <a href="./tracking/TrackerBoosting.md"><b>TrackerBoosting</b></a>
    * <a href="./tracking/TrackerBoosting.md#clear">clear</a>
    * <a href="./tracking/TrackerBoosting.md#init">init</a>
    * <a href="./tracking/TrackerBoosting.md#update">update</a>
  * <a href="./tracking/TrackerBoostingParams.md"><b>TrackerBoostingParams</b></a>
  * <a href="./tracking/TrackerGOTURN.md"><b>TrackerGOTURN</b></a>
    * <a href="./tracking/TrackerGOTURN.md#clear">clear</a>
    * <a href="./tracking/TrackerGOTURN.md#init">init</a>
    * <a href="./tracking/TrackerGOTURN.md#update">update</a>
  * <a href="./tracking/TrackerKCF.md"><b>TrackerKCF</b></a>
    * <a href="./tracking/TrackerKCF.md#clear">clear</a>
    * <a href="./tracking/TrackerKCF.md#init">init</a>
    * <a href="./tracking/TrackerKCF.md#update">update</a>
  * <a href="./tracking/TrackerKCFParams.md"><b>TrackerKCFParams</b></a>
  * <a href="./tracking/TrackerMedianFlow.md"><b>TrackerMedianFlow</b></a>
    * <a href="./tracking/TrackerMedianFlow.md#clear">clear</a>
    * <a href="./tracking/TrackerMedianFlow.md#init">init</a>
    * <a href="./tracking/TrackerMedianFlow.md#update">update</a>
  * <a href="./tracking/TrackerMIL.md"><b>TrackerMIL</b></a>
    * <a href="./tracking/TrackerMIL.md#clear">clear</a>
    * <a href="./tracking/TrackerMIL.md#init">init</a>
    * <a href="./tracking/TrackerMIL.md#update">update</a>
  * <a href="./tracking/TrackerMILParams.md"><b>TrackerMILParams</b></a>
  * <a href="./tracking/TrackerTLD.md"><b>TrackerTLD</b></a>
    * <a href="./tracking/TrackerTLD.md#clear">clear</a>
    * <a href="./tracking/TrackerTLD.md#init">init</a>
    * <a href="./tracking/TrackerTLD.md#update">update</a>
  * <a href="./tracking/MultiTracker.md"><b>MultiTracker</b></a>
    * <a href="./tracking/MultiTracker.md#addMIL">addMIL</a>
    * <a href="./tracking/MultiTracker.md#addBOOSTING">addBOOSTING</a>
    * <a href="./tracking/MultiTracker.md#addMEDIANFLOW">addMEDIANFLOW</a>
    * <a href="./tracking/MultiTracker.md#addTLD">addTLD</a>
    * <a href="./tracking/MultiTracker.md#addKCF">addKCF</a>
    * <a href="./tracking/MultiTracker.md#update">update</a>
* <a href="./text/text.md"><b>text</b></a>
  * <a href="./text/text.md#loadOCRHMMClassifierCNN">loadOCRHMMClassifierCNN</a>
  * <a href="./text/text.md#loadOCRHMMClassifierCNNAsync">loadOCRHMMClassifierCNNAsync</a>
  * <a href="./text/text.md#loadOCRHMMClassifierNMA">loadOCRHMMClassifierNM</a>
  * <a href="./text/text.md#loadOCRHMMClassifierNMAsync">loadOCRHMMClassifierNMAsync</a>
  * <a href="./text/text.md#createOCRHMMTransitionsTable">createOCRHMMTransitionsTable</a>
  * <a href="./text/text.md#createOCRHMMTransitionsTableAsync">createOCRHMMTransitionsTableAsync</a>
  * <a href="./text/OCRHMMClassifier.md"><b>OCRHMMClassifier</b></a>
    * <a href="./text/OCRHMMClassifier.md#eval">eval</a>
    * <a href="./text/OCRHMMClassifier.md#evalAsync">evalAsync</a>
  * <a href="./text/OCRHMMDetector.md"><b>OCRHMMDetector</b></a>
    * <a href="./text/OCRHMMDetector.md#run">run</a>
    * <a href="./text/OCRHMMDetector.md#runAsync">runAsync</a>
    * <a href="./text/OCRHMMDetector.md#runWithInfo">runWithInfo</a>
    * <a href="./text/OCRHMMDetector.md#runWithInfoAsync">runWithInfoAsync</a>
* <a href="./face/face.md"><b>face</b></a>
  * <a href="./face/EigenFaceRecognizer.md"><b>EigenFaceRecognizer</b></a>
    * <a href="./face/EigenFaceRecognizer.md#train">train</a>
    * <a href="./face/EigenFaceRecognizer.md#trainAsync">trainAsync</a>
    * <a href="./face/EigenFaceRecognizer.md#predict">predict</a>
    * <a href="./face/EigenFaceRecognizer.md#predictAsync">predictAsync</a>
    * <a href="./face/EigenFaceRecognizer.md#save">save</a>
    * <a href="./face/EigenFaceRecognizer.md#load">load</a>
  * <a href="./face/FisherFaceRecognizer.md"><b>FisherFaceRecognizer</b></a>
    * <a href="./face/FisherFaceRecognizer.md#train">train</a>
    * <a href="./face/FisherFaceRecognizer.md#trainAsync">trainAsync</a>
    * <a href="./face/FisherFaceRecognizer.md#predict">predict</a>
    * <a href="./face/FisherFaceRecognizer.md#predictAsync">predictAsync</a>
    * <a href="./face/FisherFaceRecognizer.md#save">save</a>
    * <a href="./face/FisherFaceRecognizer.md#load">load</a>
  * <a href="./face/LBPHFaceRecognizer.md"><b>LBPHFaceRecognizer</b></a>
    * <a href="./face/LBPHFaceRecognizer.md#train">train</a>
    * <a href="./face/LBPHFaceRecognizer.md#trainAsync">trainAsync</a>
    * <a href="./face/LBPHFaceRecognizer.md#predict">predict</a>
    * <a href="./face/LBPHFaceRecognizer.md#predictAsync">predictAsync</a>
    * <a href="./face/LBPHFaceRecognizer.md#save">save</a>
    * <a href="./face/LBPHFaceRecognizer.md#load">load</a>

