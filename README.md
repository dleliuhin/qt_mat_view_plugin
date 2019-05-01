# Qt MatView plugin

*QtDebug* helper for visualizing *cv::Mat* and *cuda::GpuMat* images.

## About

Often, Computer Vision tasks are somehow connected with images. Regardless of the chosen *IDE* for work is necessary to view the states of matrices in the *Debug Mode* which are the images themselves. The matrices are represented by the ready-made *cv::Mat* classes in *OpenCV* and *cuda::GpuMat* in *CUDA*. Since these libraries assume the use of the *C++* language the most comfortable *IDE* is *QtCreator*. Here the difficulties begin. Very often there are situations in which, well, it is very necessary to look at the states of the matrices or display the image itself on the screen, which is not yet possible in *Debug mode*. For example, to such a critical situation can be attributed to when we need to cut out *ROI* (regions of interest in the image), or vice versa to impose on the original. Switching from *Debug Mode* to *Run* takes a lot of time from the developer. Even the search for the appropriate plug-in for *Qt* did not give a significant result. I would like to create my own plugin for working with images in Debug mode.

### As pluses:

- A great way to boost *Qt* and *C++* skills;
- the tool can be written once and for all, to be used by the developers of the company in solving computer vision problems, and the next generations too;
- make the project opensource, thus share with developers around the world (we are sure that we were not the only ones who faced this problem).

## [Work plan](doc/Plan.md)

## [General requirements](doc/Reqs.md)

## [License](doc/LICENSE)
