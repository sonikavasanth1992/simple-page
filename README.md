const brusher = new Brusher({
  image: 'abstract.png', // Path of the image to be used as a brush
  keepCleared: false, // Whether to keep cleared sections or blur them again
  stroke: 80, // Stroke size for the brush
  lineStyle: 'round', // Brush style (round, square, butt)
  autoBlur: false, // Brusher will use the provided image for the blurry background
  autoBlurValue: 15, // Blur strength in pixels
});

brusher.init();
