# Licence-Plate-Detection-and-Recognition-using-YOLO-V8-EasyOCR
📌 What is this project about?

Imagine cars driving on the road. Every car has a license plate (the number plate with letters and numbers).
This project is like giving a computer “super-eyes” 👀 so it can:

Find the license plate on the car.

Read the letters and numbers written on the plate.

Tell us the result quickly, just like a traffic police camera would do.

So basically, this project teaches a computer to look at a car, spot the plate, and read what’s written on it.

⚙️ How does it work? (In simple words)

Collecting Data 🖼️

I used 948+ images and 8+ videos of cars from a dataset (Roboflow).

These images were labeled (we drew boxes around license plates) so the computer knows what a plate looks like.

Training the Model (YOLOv8) 🧠

YOLOv8 is like a very smart robot brain for looking at pictures.

I taught this robot to recognize license plates using the images.

After enough practice, it became very good (98.5% accuracy 🎯).

Detecting License Plates 🚙➡️📷

When you show a new car picture or video to the trained model, it instantly finds the license plate.

Reading the Plate (OCR) 🔡

After the plate is found, I used EasyOCR (a text-reading tool) to read the letters and numbers.

Example: A plate like KA05AB1234 gets detected and read correctly.

Making it Fast & Useful ⚡

I added OpenCV for better image processing (cleaning up the plate before reading).

I built a secure API so that this project can be used in real life (like at toll gates, parking lots, or traffic signals).

🛠️ Tech Stack (Tools I used)

YOLOv8 → Finds where the license plate is.

OpenCV → Cleans up images and makes them easier to read.

Python → Programming language that connects everything.

EasyOCR → Reads the letters/numbers on the plate.

Roboflow Dataset → Source of images and videos for training.

🚀 Why is this useful?

Traffic police can catch rule breakers faster.

Parking systems can automatically note cars coming in/out.

Toll booths can collect money without stopping cars.

Smart cities can keep track of vehicles automatically.

🏆 Results

Accuracy: 98.5% (means it almost never makes a mistake).

Speed: Works in real-time (instantly detects plates from videos).
