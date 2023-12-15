# Translator Robot: PolyglotBot

## Video Demo

The following demonstration is at 5x speed:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/FzNauYVdgLc?si=t54-GzDRyTJkSKZ6"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

## Description

In the 'Embedded Systems in Robotics' course from Northwestern University's Master of Science in Robotics program, my team's final project involved designing and programming an autonomous system, capable of scanning, translating, and physically writing both written and spoken words or phrases from any language to any desired language. This series of tasks was performed by a Franka Panda Robot Arm, which executed the action of writing the translations onto a whiteboard.

The system comprises of several key components:
1. An overarching state machine governing the system's overall behavior.
2. A camera setup incorporating Object Character Recognition (OCR) to capture and input written text.
3. A translation module utilizing APIs to translate the input text into a selected target language.
4. A waypoint generator for creating a series of robot arm movements based on the translated text.
5. A customized arm controller, which is used for the robot arm's precise movements according to the generated waypoints and other actions, like picking up a marker or returning to its starting position. This involved adapting our custom ROS MoveIt package for handling numerous waypoints.
6. Additional sub-systems, such as speech-to-text processing for verbal inputs and camera systems for distance calibration relative to the whiteboard.

My primary focus was on the translation module and the arm controller. I also served the role as the team's Systems Integrator, coordinating team efforts to ensure seamless integration of each subsystem and managing our git workflow for effective version control and collaboration.

This project was the culmination of the 'Embedded Systems in Robotics' course, challenging myself and my cohort to apply the wide range of robotics concepts we learnt in a practical setting. It also provided invaluable experience in team collaboration and robotics system design within a set timeframe, skills that I am excited to carry forward in my future professional and academic endeavors.

***Date:*** November 2023 - December 2023

## Gallery
### Videos

Picking Up & Putting Down Marker:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/FzNauYVdgLc?si=t54-GzDRyTJkSKZ6"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Speech Translation:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/KhQWWGM9iRM?si=OOhAZMiVLYY0N3dI"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/KhQWWGM9iRM?si=OOhAZMiVLYY0N3dI"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Latin to Non-Latin Translation:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/FzNauYVdgLc?si=t54-GzDRyTJkSKZ6"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Non-Latin to Latin Translation:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/ZGGghOw5x7E?si=vDHbWZ39mUDPwb0D"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Non-Latin to Non-Latin Translation:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/KhQWWGM9iRM?si=OOhAZMiVLYY0N3dI"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Non-Latin to Non-Latin Translation:

<iframe
    width="560" height="315"
    src="https://www.youtube.com/embed/KhQWWGM9iRM?si=OOhAZMiVLYY0N3dI"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

### Images

<img src="https://github.com/dkoh555/dkoh555.github.io/assets/107823507/74b8a6f1-8425-42e0-a6d4-a464df5a5f97" height="300">
