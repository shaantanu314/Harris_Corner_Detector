<br />
<p align="center">


  <h3 align="center">Harris Corner Detector</h3>

  <p align="center">
    An implementation of a simple Harris corner detector in python
    <br />
    <hr>
    <h3>
    The Harris corner detection algorithm is one of the simplest corner detectors available. The idea is to locate interest points where the surrounding neighbourhood shows edges in more than one direction. The basic idea of algorithm is to find the difference in intensity for a displacement of (u,v) in all directions which is expressed as below:
    </h3>
    <br>
    <div style="text-align:center"><img src="./equations/main.png" style="width:50%" /></div>
    <br>
    <h3>This code follows the steps given below to get the output:
    <ul>
    <li> Conversion of Image to grayscale (We are only interested in intensities)</li>
    <li> Calculation of the image gradient along x and y direction</li>
    <li>Harris response calculation by running required window over the image</li>
    <li>Finding the edges and corners by comparing harris response with threshold values</>
    </h3>
    <hr>
    <h2>Example Output of the algorithm</h2>
    <div style="text-align:center"> <h3>Sample Input Image</h3> <br><img src="image.jpg" style="width:50%" /></div>
    <div style="text-align:center"> <h3>Output Image</h3> <br><img src="Harris_corner_detector_output.png" style="width:100%" /></div>
    
  
  </p>
</p>
