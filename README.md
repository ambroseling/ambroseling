
# Hi there its Ambrose👋

# A little bit about myself...
<p align="center">
        <a href="" target="_blank" rel="noreferrer">
    <img
      src="https://github.com/ambroseling/ambroseling/assets/93873940/bb0370c1-1fe1-40cb-ac54-ce241ae59657"
      alt=""
      width="250"
      height="250"
    />
  </a> 
</p>

Hello hello! I'm Ambrose Ling in third year ECE with a double minor in Artifical Intelligence and Engineering Entrepeneurship.
I love exploring machine learning applications, playing with electronics, doing fun software projects, making the world a better place with technology. I also love a good cup of coffee, playing chess and football. Feel free to connect with me through the channels below !

## Neurosience/Deep Learning Research @ LinLabs
In the summer of 2023, I worked on a neuroscience research project with Professor Qian Lin that aims to study the neurodynamics of zebrafish behaviour in spatial recognition and task learning. My research contributed to 2 areas:

**Zebrafish tracking**
- Implemented computer vision tracking with ResNet50, MobileNet architectures, achieved tracking accuracy of 75%+ 
- Preprocessed images by applying normalization,resizing and scaling,used K-means clustering to segregate frames; preprocessed labels by converting coordiantes to gaussian distributed heat map 
- Optimized real-time tracking prediction speed by 55% (measured by timer) with parallel computing in Tensorflow, that would help minimize the latency in the experimental system
- Designed image preprocessing software, allowed other students to label images and speed up experiments
- Instructed other lab members on how to use tracking software such as the web app, stytra, deeplabcut
- Leveraged GPU to speed up tail tracking model training
- Assisted with hardware testing
- Helped facilitate socket connections from Stytra Python to Unity

For more details and code, check out our [repo](https://github.com/ambroseling/Zebrafish-DeepLabCut)

**Locomotion Prediction** 
- Presented papers on continous time recurrent neural networks, Neural ODE networks, LTC networks in journal clubs
- Implemented the benchmark autoregressive model for predicting zebrafish movement in VR, clearly demonstrated weaknesses in their model and datasets
- Preprocessed public  tail deflection datasets by using noise reduction, local polynomial interpolation, normalization to handle uneven sampling
- Optimized movement predictions by developing our own multi layer GRU model, LTC model, and GRU encoder-LTC decoder model, beat the benchmark by 5% in MSE reduction, 6% in R^2 score increase
- Presented locomotion prediction research at Undegraduate engineering research conference, awarded Best Overall Poster Presentation
- Demonstrated a comprehensive model performance comparision, conducted parameter search to find best optimal working model

For more details and code, check out our [repo](https://github.com/ambroseling/Zebrafish-DeepLabCut)


## LINKUPSS Co.
- **LINKUPSS**: A tech start-up aiming to simplify technology for seniors through accessible online resources.
- Collaboration with:
  - Day-care centers
  - Community centers
  - Engineers
- Mission: Bridge the digital divide across generations.
- Currently in UofT Entrepreneurship Hatchery program.
- Advisory board of industry professionals assisting with:
  - Business plan development
  - Market research
  - Customer outreach
  - Cashflow projections
- Facilitated connections with:
  - 116+ senior organizations
  - 200+ seniors in Ontario, Canada
  - 40 organizations implementing solutions
- Goal: Expand outreach to more organizations and seniors.
- Awarded [Google Solutions Challenge 2023 Global Top 100 Qualifiers](https://www.youtube.com/watch?v=1npCEqfD8k4&t=15s) out of 2000+ teams worldwide.
- Mentorship from Google engineers and designers, leading to continuous design improvements.
For more information, feel free to contact and visit our [LINKUPSS website](https://www.linkupss.com)!

## Tensorflow Developer Certification
I have completed the **Tensorflow Developer Certification** from Google. 
During this certification journey, I have accomplished the following:
- Developed a range of ML models including:
  - Binary and multiclass classification
  - Linear regression
  - Image classification
  - Object detection
  - Natural language processing
  - Text generation
  - Time-series analysis
  - Sequential analysis


I believe this achievement effectively showcases my competence in machine learning and positions me for further opportunities in the field.
To explore my exam preparation repository [here](https://github.com/ambroseling/Tensorflow).

Some sample models:
- Bitcoin Price Predictor [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1X2nghZTOzs9u5lgMzETvQSN4jhz7tAsy)
- Tweet Disaster Classificatoin NLP [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13XAe8Hy_F3tCuDsWR55xzJlxI4BbihYy)
- Food 101 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1epo8WlfpE4FSRaQ6BIE14niTFKPZlkSt)

## Course Work
### RoastRoute: Coffee Date GIS (Software Communication & Design)
Our team of 3 developed a **GIS platform** using the following technologies:
- GTK
- C++
- FastAPI
- OpenStreetMapAPI
This platform enables users to efficiently organize coffee dates. Our project includes the following achievements:
- Implemented **Dijkstra's algorithm** with multithreading for path-finding.
- Achieved impressive computation times: less than 0.15 seconds for paths above 15 km.
- Addressed the traveling courier problem using the **Greedy algorithm**.
- Incorporated local perturbations to enhance path quality by more than 15%.
  
For more details, explore [our repository](http://ug251.eecg.utoronto.ca/wiki297s/doku.php?id=cd019:start).

### BuzzWire: ARM Cyclone V DE1-SoC (Computer Organization and Architecture)
**BuzzWire** is a hardware game designed to test players' focus and skills in navigating an exciting metal wire obstacle course using a wand. The key features of this project include:
- Integration of the **DE1-Soc board** with circuitry.
- Reading voltage changes from the Analog to Digital Converter port to detect player interactions with the wire.
- Utilizing the **A9 Private Timer** to enforce a 30-second time constraint for players.
- Displaying a graphical user interface through the **VGA display** to indicate game progress and outcomes.
- Playing an explosion sound effect via the **Sound & Audio I/O** ports when players lose.
- A collaborative effort by Areeba and myself, resulting in a rewarding experience.

For more in-depth information, please visit [our repository](https://github.com/ambroseling/BuzzWire).


### ARM 16 bit Processor: ARM Cyclone V DE1-SoC (Computer Organization and Architecture)
Our collaborative effort resulted in the development of a processor using **System Verilog**, designed to execute essential **ARM Assembly instructions** on the **ARM Cyclone V DE1-SoC board**. The project highlights include:
- Step-by-step construction of different components.
- Utilization of **KEY buttons** and **TOGGLE switches** as input methods for instruction execution.
- Displaying output on the **HEX display** and LED lights.
- Incorporation of **ModelSim** for simulation, debugging, and testing purposes.
- A challenging yet rewarding experience that culminated in a functional processor.

For detailed insights, please explore [our repository](https://github.com/ambroseling/ARM-Processor).

### Reversi: Turn-based strategy Game in C (Introduction to Programming in C/C++)
I successfully created an **artificial intelligence** capable of playing the turn-based strategy board game, **Reversi**. My achievement included the following:
- Implementation of the **MinMax recursive algorithm** for decision-making.
- Outperformance against the majority of bots in our class.
- Ranking **57th** out of over **250+ students** in the class competition.

For a deeper understanding, feel free to explore [the repository](https://github.com/ambroseling/Reversi).


# Connect with me !
<p align="left">
<a href="https://www.linkedin.com/in/ambrose-ling/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="" height="30" width="40" /></a>
<a href="https://www.youtube.com/channel/UCr3NDxv6PlXOAgloNPzpK8Q" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="" height="30" width="40" /></a>
<a href="https://discordapp.com/users/ambroseling1015" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="" height="30" width="40" /></a>
</p>
