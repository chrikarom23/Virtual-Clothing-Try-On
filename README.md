# Virtual-Clothing-Try-On
A virtual cloth try on program using mediapipe, cv2 and PIL libraries.

The primary objective of virtual clothing try-on applications is to 
improve the shopping experience for customers by allowing them to 
virtually try on clothes and accessories before making a purchase. This 
technology can help customers make more informed decisions by providing 
them with a more realistic sense of how the clothes will fit and look on them. 
By reducing the number of returns and exchanges, virtual try-on applications 
can also save retailers time and money.

Architecture Diagram:<br>
<img width="197" alt="image" src="https://github.com/chrikarom23/Virtual-Clothing-Try-On/assets/66157915/b8c56dd5-3fe9-4cfb-af92-bf49d38a388b">



Using said libraries along with the grabcut algorithm to get the apparel we can overlay 
the apparel, real time, on top of the user to display as if the user is wearing the apparel.

Future Work:
1. Developing a user interface: As of now our program is solely dependent 
on the programmer giving inputs to it directly. In future iterations it will be made 
so that any user can easily run this program.
2. Improving apparel position estimation: To improve the apparel 
position estimation so that it provides a much better view of the apparel on the 
user.
3. Adding filters: One of the objectives of this program is to implement 
lighting conditions on to the apparel similar to the lighting condition the user is 
currently in or wants to replicate.
 4. Segmenting cloth sections: Cloth sections can be segmented to 
accommodate movements to provide a more lifelike feel to the program
