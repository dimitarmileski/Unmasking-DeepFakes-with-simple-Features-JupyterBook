# Introduction

## Unmasking DeepFakes with simple Features
Ricard Durall<sup>1,2,3</sup> Margret Keuper<sup>4</sup> Franz-Josef Pfreundt<sup>1</sup>
Janis Keuper<sup>1,5</sup>   
<sup>1</sup>Fraunhofer ITWM, Germany   
<sup>2</sup>IWR, University of Heidelberg, Germany   
<sup>3</sup>Fraunhofer Center Machine Learning, Germany   
<sup>4</sup>Data and Web Science Group, University Mannheim, Germany   
<sup>5</sup>Institute for Machine Learning and Analytics, Offenburg   University, Germany   


Over the last years, the increasing sophistication of smartphones and the growth of social networks have led to a gigantic
amount of new digital object contents. This tremendous use
of digital images has been followed by a rise of techniques
to alter image contents. Until recently, such techniques were
beyond the reach of most users since they were dull and
time-consuming and they required a high domain expertise on
computer vision. Nevertheless, thanks to the recent advances
of machine learning and the accessibility to large-volume
training data, those limitations have gradually faded away.
As a consequence, the time for fabrication and manipulation
of digital contents has significantly decreased, allowing even
amateur users the modification of contents at their will.


<p align='center'>  
    <img align="center" src="03/imgs/pipeline.PNG" width="500"/>
</p>



Overview of the pipeline used in our approach. It contains two main blocks, a pre-processing where the input istransformed to a more convenient domain and a training block, where a classifier uses the new transformed features to determine whether the face is real or not. Notice that input images are grey-scaled before DFT.