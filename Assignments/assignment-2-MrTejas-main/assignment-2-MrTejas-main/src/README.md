# Assignment 2 - Report
**Name :** Tejas Srivastava
**Roll No. :** 2021102017
**Course :** Digital Image Processing

## Question 1

We know that number of bits in 1 image is given as
$$
num\ bits\ =\ 720\ \cdot\ 480\ =\ 345600\ bits
\\
\ total\ space\ available\ =\ 2GB\ =\ 2\cdot1024\ mb\ =\ 2\cdot\left(1024\right)^{2}\ kb\ =\ 2\cdot\left(1024\right)^{3}\ bytes
\\
$$

$$
number\ of\ images\ =\ \frac{\left(\ total\ space\ available\right)}{\left(num\ bits\right)}=6213.78\ =\ 6213\ images
$$

Thus we can store **6213** images on cloud.

## Question 2

Following are the observations from the bit-planes obtained on slicing the given image :-
- In the bit-plane 0 (LSB), maximum noise is present, almost no information about the image is conveyed, thereby making it useful for data stenography and data hiding in images. Except for the centre of explosion, where most of the pixels are similar and there is little variance, most of the places consist of noise only.
- Moving to higher bit planes, the noise is still present but starts taking shape of the explosion slowly.
- At the 2nd bit-plane, the waves of explosion can be seen, however in none of the images is the colour correctly displayed. 
- Only in the last bit plane (bit plane 7), can the colour be seen somewhat clearly (Red and Yellow) due to small difference between the actual values and the sliced values.

## Question 3

Before contrast stretching :-
- Darker colors are present in the image's colorbar, mostly shades of pink.

After contrast stretching :-
- The most frequent colors change their intensity to higher values. Most of the colors present are still various shades of pink
