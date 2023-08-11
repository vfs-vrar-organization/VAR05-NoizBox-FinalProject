# NoizBox
Designed & Developed by Ben Westergreen

![GIF_Intro](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/MainImage.gif)

> NoizBox is an experimental virtual reality (VR) spatial audio project developed with Unity Engine. It emerged from explorations to create a synesthetic VR experience that celebrates body autonomy and empowers users to connect with rhythm and sound on a personal level.

# Agency - Redefining XR Rhythm Experiences
NoizBox is built on the value of agency, where users have control over their experience. Unlike traditional rhythm games that dictate specific movements and note maps, NoizBox opens up a world of possibilities, enabling users to engage with music on their terms. The emphasis on agency fosters creative expression and individuality, encouraging users to connect with rhythm in a personal and authentic way. 

As a solo project, NoizBox had inherent limitations. Conducting a comparative analysis of existing rhythm games and sound synthesis experiences provided valuable insights. While I drew inspiration from synthesis-focused apps like PatchXR and Synth VR, the focus of NoizBox was playing and layering existing sound loops and one-shots.

# Concept Development - Visual Aesthetics and Mood

![GIF_NarrativeDev_1](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Concept%20Development%20-%20Visual%20Aesthetics%20and%20Mood.gif)

During concept development, I embarked on a parallel exploration of narrative and visual aesthetics. Using Midjourney, I rapidly iterated on styles and moods, seeking to create a sense of scale that VR affords, allowing users to immerse themselves in captivating scenes that resonated with their emotions.

# Prototype 1: Interactive Sound Objects

![GIF_PrototypeOne](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Prototype%201%20Interactive%20Sound%20Objects.gif)

NoizBox's early stages saw the birth of Prototype 1, where the focus was on interactive sound objects. The project introduced audio reactive cubes, representing sound objects, which users could play, move, and manipulate within the virtual space. These cubes dynamically changed color and size based on audio intensity, creating visually expressive particle effects that resonated with the audio. The success of Prototype 1 validated the potential of 3D spatial audio for sound design and provided a foundation for further exploration.

> Playtesting Insights
Playtesting Prototype 1 provided valuable insights into user behavior and preferences. Users expressed a desire to explore the virtual environment more openly, often venturing off the guided path and into the virtual woods. As I explored ways to guide users while allowing for open exploration, striking a balance between narrative guidance and unrestricted movement proved to be a significant challenge. The dynamic nature of soundscapes and user interactions made it difficult to predict user trajectories and maintain a cohesive audio narrative.

# Prototype 2: Collecting Audio Objects with Orbital Motion

![GIF_Orbital](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Prototype%202%20Collecting%20Audio%20Objects%20with%20Orbital%20Motion.gif)

Prototype 2 centered around the innovative concept of collecting audio objects and their orbital motion around the user's hand. By introducing a dynamic element of randomness to the orbits, I aimed to create an engaging and immersive experience. While the concept was experimental and engaging, I realized the importance of grounding ideas in the overall user flow. Balancing creativity with user-centric design became crucial to ensure a seamless and intuitive experience.

# Style Frames and Generative Cube Rooms

![GIF_StyleFrame](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Style%20Frames%20and%20Generative%20Cube%20Rooms.gif)

Style frames were instrumental in honing the aesthetics of NoizBox. Through quick gesture digital paintings, I experimented with various visual styles, eventually leading to the creation of the generative cube rooms. These captivating and ever-changing spaces allow users to lose themselves in a symphony of visuals that respond to their movements and actions.


## Generative Tools: A World of Dynamic Environments

![GIF_GenerativeCreature](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Generative%20Tools%20A%20World%20of%20Dynamic%20Environments.gif)

The development of generative tools opened a world of possibilities for NoizBox's environments. By adapting the "generative creature" code from Eliza Struthers-Jobin, I explored ways to sync her creature to a BPM and allow user-controlled acceleration based on the effect intensity of specific sound cubes.

# Prototype 3: Gyroscope Filter and Audio Control

![GIF_Gyroscope](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Prototype%203%20Gyroscope%20Filter%20and%20Audio%20Control.gif)

Inspired by the Orba, Prototype 3 incorporated the gyroscope filter into NoizBox's sound objects, providing users with an exciting and satisfying way to control volume, distortion, and low-pass filtering. The combination of multiple control types within a single object aimed to enhance the user experience and creative expression.

> User Testing Insights
While the gyroscope filter added a layer of interactivity, user testing exposed the challenges of combining various interactions without clear feedback. The lack of intuitive responses left users feeling uncertain about the changes they were making to the sound.

# Prototype 4: Layered Audio Experience

![GIF_NarrativeProto](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Prototype%204%20Layered%20Audio%20Experience.gif)

Prototype 4 explored a linear approach to guide users through a curated series of sounds that naturally layered and built upon each other. Users unlocked the next sound object by interacting with the current one for a set time. The challenge lay in quickly prototyping different sound samples to discover how they could combine and layer, guiding users through the journey.

> Opportunities from Obstacles
During this exploration, a critical realization emerged - the absence of a tool to rapidly prototype various sound samples in a spatial environment. This obstacle presented a unique opportunity for NoizBox's transformation into a powerful spatial audio tool, allowing users to create and experiment with layered compositions effortlessly.

# Generative Artwork and User-Centric Design

<img width="1160" alt="GeneratedCoverArt" src="https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Generative%20Artwork%20and%20User-Centric%20Design.png">

To enrich the display of audio samples I took inspiration from sound applications like FractalBits and the humanistic approach to DataViz in "DearData" by Giorgia Lupi and Stefanie Posavec. I used an AI Image Generator Midjourney to create a catalog of imagery for a curated selection of audio samples. My prompts were based on descriptions of what each sound sounded like, and AI allowed me to generate over +200 distinct images. The generated images were sorted based on affinity attributes and reassigned to instruments.

# Frontend Framework and Visual Design

![GIF_UIDesign](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Frontend%20Framework%20and%20Visual%20Design.gif)


The project's frontend framework, Nova UI, accelerated the prototyping speed by allowing the creation of basic shapes and assets directly in the editor. Early testing and visual design for interactions were facilitated using a 2D wireframe and prototype in Figma.

# Lighting and Optimization

![GIF_Lighting](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Lighting%20and%20Optimization.gif)

I focused on making the experience smoother and more visually appealing with lighting and optimization of the scene. This involved baking lights and making objects static to enable static and dynamic batching, leading to significant performance improvements. The introduction of high-quality soft lighting through the bakery added an artistic touch and enhanced the visual aesthetics. Additionally, dimmer lit scenes were carefully designed to create a comfortable environment for audio creation and extended play sessions.

# Audio Objects - Modular Design

![GIF_Modular_1](https://github.com/VFS-VRAR/VAR05-NoizBox-FinalProject/blob/main/Images%20And%20GIFs/Audio%20Objects%20-%20Modular%20Design.gif)

NoizBox's audio objects embrace a modular design, offering a flexible and adaptable foundation for the project. Effect panels for loops and one-shots add depth to user interaction. Loops feature effect levers for control over filters and distortion, while one-shots include drum pads for triggering sounds. The modular audio objects in NoizBox become the canvas for users to paint their sonic stories.

# Case Study Video

[![NoizBox Case Study Video](https://img.youtube.com/vi/Bjy21NrGmhI/0.jpg)](https://youtu.be/Bjy21NrGmhI)

## Future Additions: Expanding Creativity and Collaboration
Features I would like to explore to expand and enhance NoizBox:

- User Customization: Import your own audio and art for a personalized experience.
- Full AR Functionality: Embrace upcoming devices like Quest 3 and Apple Vision Pro for immersive AR experiences.
- Audio Reactive Elements: Witness the environment come alive, responding to sound intensity.
- Enhanced Effect Panels: More tools to shape sounds and compositions.
- Collaboration with Professionals: Partner with sound designers, producers, and performers for specialized tools.
- Live Performance and Collaboration: Connect in real-time for mesmerizing audio and visual experiences.
