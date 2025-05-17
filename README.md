# emotion-visual-masks
This repository contains visual examples of custom visual feature masks used in my Bachelor's thesis on emotion perception. The goal of the project was to explore whether specific local orientation features influence the way participants perceive emotional intensity in facial expressions. To train the model, different types of noise and distortion had to be applied to the images. Several of my visual masking ideas are shown below. 
Note: Original face images are from the Radboud Faces Database (RaFD) and are shown here as derivative examples for academic illustration only.
Code used for mask generation is available upon request.

## Example 1: Progressive Masking with Varying Block Sizes and Angles
 <img width="1710" alt="Screenshot 2025-05-17 at 15 43 36" src="https://github.com/user-attachments/assets/8106d103-eabe-4492-a8af-5ae2eb10a8e4" />
The image above displays 10 steps of increasing distortion, where both the block size** and rotation angle of the masking pattern are systematically varied.

## Example 2: Fixed Block Size with Increasing Rotation
<img width="1710" alt="Screenshot 2025-05-17 at 15 45 56" src="https://github.com/user-attachments/assets/cc17ea1c-aaa7-482c-a03d-95936fb5a776" />
In this second example, the block size remains constant while the rotation angle increases.

## Example 3: Sinusoidal Distortion with Increasing Amplitude and Frequency
<img width="1710" alt="Screenshot 2025-05-17 at 15 46 26" src="https://github.com/user-attachments/assets/a817b0ca-82cb-4180-90a8-b5d9852f952d" />
In this third example, sinusoidal distortions were applied to create zig-zag interference patterns that progressively increased in amplitude and frequency.

## Example 4: Spiral Masking Inspired by the Fibonacci Sequence
<img width="1710" alt="Screenshot 2025-05-17 at 15 48 09" src="https://github.com/user-attachments/assets/6ccb9864-7858-4f55-9ac8-3a93342918af" />
This example uses a spiral-based masking technique inspired by the Fibonacci (or logarithmic) spiral. The radius of the spiral increases step by ste. The spiral masking allows for a smooth, non-linear way to progressively disrupt key facial regions such as the eyes and mouth, while still maintaining an overall view of facial structure.

## Example 5: Shifted Spiral Masking
<img width="1710" alt="Screenshot 2025-05-17 at 15 51 29" src="https://github.com/user-attachments/assets/c784d3ff-e38e-44cd-873b-6097b8b27f35" />
This example is a variant of the spiral masking technique, where the image appears to shift with the growth of the spiral. As the spiral expands, it covers and reveals different parts of the face along a curved trajectory. Unlike the fixed-center version in Example 4, this approach introduces spatial shifts that affect facial alignment. 

## Example 6: Polygon-Based Occlusion
<img width="1710" alt="Screenshot 2025-05-17 at 15 54 39" src="https://github.com/user-attachments/assets/3eb5b059-4c57-4705-b412-9820fdfb1459" />
This example shows randomly placed polygon masks with increasing quantity and decreasing opacity.

## Example 7: Gabor Noise on Horizontal Features
<img width="1710" alt="Screenshot 2025-05-17 at 15 56 11" src="https://github.com/user-attachments/assets/23bfc0eb-5701-4a62-81fc-804046f37bb8" />
This example uses progressively increasing Gabor noise with a horizontal orientation to occlude facial features that are most critical for emotion recognition
