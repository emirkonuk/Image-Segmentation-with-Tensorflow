# Image-Segmentation-with-Tensorflow

My experiences using Tensorflow for image segmentation.

Includes:
- Another 'Getting Started', mainly focusing on the usage of feed_dict mechanism (with and without placeholders)
- The most basic network creation method: Stacking layer after layer sequentially
- U-nets for segmentation
- Links to various websites, lecture notes, etc. for tips and tricks
  - How to select stddev for weights,
  - How to use both queues and placeholder/feed_dict mechanism in a single graph,
  - Explanations of various Tensorflow functions including conv2d_transpose,
  - Explanations for queues, input pipelines, TFRecords, WholeFileReader etc.
- Using variable_scope to convert the previous basic network into a more concise/readable format
- OpenCV FileIO to read/write 64 bit images to a .yml file using python
- Using queues to train the network
- Reading/writing a TFRecords file with and without batching
- My own questions regarding all these topics
