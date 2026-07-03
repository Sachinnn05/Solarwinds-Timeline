🔍 SolarWinds Attack: An Interactive Timeline

About This Project

This is my submission for the Week 2 Cyber Attack Timeline Project. I chose to research the 2020 SolarWinds supply chain attack because of how massive and complex it was. Instead of just writing a list of dates, I wanted to build something visual to show exactly how the hackers got in, how they stayed hidden, and the sheer scale of the damage.

This repository holds the code for the interactive timeline prototype that goes along with my main research report.

How to View the Timeline

There is no complicated setup needed to run this project!

Download the index.html file from this repository to your computer.

Double-click the file to open it in your default web browser (it works great on Chrome, Firefox, or Safari).

Click through the different phases on the timeline to read the details and see the SVG visuals for each step.

What I Built With

For this prototype, I wanted to keep it lightweight and fast, so I built it entirely from scratch using:

HTML5 for the basic structure.

CSS3 for the styling. I spent some time adding a custom background, blur effects (glassmorphism), and animations to make it feel like a real cybersecurity dashboard.

Vanilla JavaScript to handle the interactivity, like the expanding and collapsing accordion logic when you click on an event.

Inline SVGs instead of image files, so everything loads instantly without needing a separate images folder.

Key Takeaways from My Research

Building this timeline helped me realize just how patient these attackers were. My biggest takeaways from researching this were:

Supply Chain Vulnerability: Hackers don't need to break into a secure network if they can just compromise the software updates the network already trusts.

The Golden SAML Attack: The way the hackers forged security tokens to bypass Multi-Factor Authentication was incredible (and terrifying).

Zero Trust is Mandatory: The old "castle and moat" style of security is dead.
