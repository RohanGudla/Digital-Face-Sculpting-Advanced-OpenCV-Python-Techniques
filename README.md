# Face Alignment with OpenCV and Python

This project focuses on aligning faces using OpenCV and Python. You can refer to the detailed article at [https://www.pyimagesearch.com/2017/05/22/face-alignment-with-opencv-and-python/](https://www.pyimagesearch.com/2017/05/22/face-alignment-with-opencv-and-python/) for more information.

## Dependencies

Before running the project, make sure you have the following dependencies installed:

- `imutils` (install with `pip install imutils`)
- `dlib` (install with `pip install dlib`)
- `opencv-python` (install with `pip install opencv-python`)

Additionally, you'll need to download the `shape_predictor_68_face_landmarks.dat` file and save it in your Python project's root directory.

## Usage

To use this project, run the following command, replacing `"your origin image data dir"` with the directory containing your original image data and `"your dest dir"` with the destination directory:

```bash
python align_faces.py -r "your origin image data dir" -d "your dest dir"
```

This project will align faces in the images from the source directory and save the aligned faces in the destination directory.

Please note that the article linked above provides detailed insights into the face alignment process, and you can refer to it for a better understanding of how the project works.