# eye.mouse
ai-webcam
THIS IS WHAT MY CODE IS DOING IN TEXT FORMAT.
 The code starts by importing the necessary libraries.
 The code then creates a variable called cam, which is used to capture video from the webcam.
 Next, it creates a face mesh object and assigns it to the variable face_mesh.
 Then, it sets up variables for screen width and height in pixels using pyautogui's size function.
 The while loop starts by reading frames from camera one frame at a time until there are no more frames left or until the user presses ctrl+c on their keyboard to stop capturing video.
 The first thing that happens in each frame is that rgb_frame is created with cv2's cvtColor function and then processed with face_mesh's process method so that landmarks can be extracted from them later on in this program.
 After processing each frame, landmark coordinates are saved into an array of points called landmarks_points[0].
 Then x coordinate of each point is calculated based on its y coordinate using int(landmark) * screen width/height * x where x = int(landmark).y * screen width/height * x .
 This will give us coordinates for all of our landmarks as well as how far away they are from our mouse cursor (left side).
 Next we
 The code is a Python program that will take a video of the user's face and convert it into a mesh.
 The mesh will be used to generate an image on the screen where the user can move their head around in order to see what they would look like if they were using augmented reality.
