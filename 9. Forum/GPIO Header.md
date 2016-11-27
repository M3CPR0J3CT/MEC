G 2016 06 20
Having received the Starter Kit alongside the Zero, the question came to me: What type of GPIO Header shall we use onboard MEC?

From an electrical perspective, Female and Male headers are identical - their purpose.
From a Mechanical and Load Factor, a Female Header rack will probably be stronger and less sensitive to shocks and Vibrations than its Male counterpart.

[Fig. 1] GPIO Female Header

But from a Moisture and Dust Ingress viewpoint, the Female Header may be more vulnerable.

[Fig. 2] GPIO Male Header

As a first guess, I would go for Female Headers on the Pi or Zero and protect it in a (bottom) vented shield (cf. MEC.F9, 12 and 16).
We already have both Jumper Wires anyway.

B 2016 08 05
Agreed, the female header would be best against vibration. The case/aircraft can provide the required IP rating.

G 2016 08 06
Added the IP Ratings description to the Technical Library.
