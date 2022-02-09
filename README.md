Real-world dynamic programming: content-aware image resizing
============================================================
There are four steps in the implementation:

| Step | Exercise file | Description                                |
|------|---------------|--------------------------------------------|
| 1    | `energy.py`   | Energy calculation                         |
| 2    | `seam_v1.py`  | Finding the lowest-energy seam (version 1) |
| 3    | `seam_v2.py`  | Finding the lowest-energy seam (version 2) |
| 4    | `carve.py`    | Removing seams from the image              |

Each step is documented at the top of the exercise file.

The code in the different steps are put together in the final step, but each step has some code written for you that allows you to visualize the progress up to that step.  For example, the energy calculation is what drives the seam carving process, but `energy.py` allows you to visualize the calculated energy if you run the file in isolation.

Setup
-----

1. Ensure you have Python 3 installed.
1. Install the dependencies using `pip`: `pip install -r requirements.txt`

1. Now you should be able to implement and run the code as explained at the top of each exercise file.


Image credits
-------------

All images are free to redistribute. Attribution is not necessary, but encouraged:

- Surfer - [Kiril Dobrev](https://pixabay.com/users/kirildobrev-12266114/) on [Pixabay](https://pixabay.com/photos/blue-beach-surf-travel-surfer-4145659/)

- Arch - [Mike Goad](https://www.flickr.com/photos/exit78/) on [Flickr](https://flic.kr/p/4hxxz5)
