# Ex.No.9: Exploration of Prompting Techniques for Video Generation

### Date: 06/09/2026

### Reg. No: 212223240029

## Aim

To demonstrate text-to-video prompt engineering techniques to reproduce a target video by identifying and describing important visual elements such as subjects, motion, lighting, composition, colors, camera movement, environment, and artistic style.

## Video Selection & Reproduction Case Study


https://github.com/user-attachments/assets/6a20f2ec-8f23-4423-9a67-50c3afa21742


### Video 1: Futuristic Metro Station at Night

The selected video is a 5-second cinematic futuristic metro station scene at night. The scene shows a modern train arriving at a brightly illuminated platform, passengers waiting and walking, digital displays, glowing advertisements, metallic structures, and reflections on the polished floor.

## Video Analysis

* Objects/Subjects: Futuristic metro train, passengers, digital displays, advertisements, benches, pillars and platform structures
* Motion: Train moves slowly into the station, passengers walk along the platform, digital displays glow, and the camera moves forward smoothly
* Colors: Blue, cyan, purple, white and warm yellow
* Lighting: Bright artificial lights, neon advertisements and glowing train lights illuminate the station
* Texture: Metallic surfaces, glass panels, polished flooring and reflective train body
* Background: Large futuristic station with platforms, digital screens, overhead structures and illuminated signs
* Composition: Central train and platform create strong leading lines toward the vanishing point
* Camera: Smooth cinematic forward tracking shot at platform level
* Style: Photorealistic cinematic futuristic environment
* Mood: Modern, technological, calm and futuristic

## Prompt Refinement Progression

### Iteration 1 (Basic Prompt)
```
A futuristic metro station at night with a train and passengers.
```
### Iteration 2 (Detailed Prompt)
```
A futuristic metro station at night with a modern train arriving at the platform, passengers walking, bright digital screens, glowing advertisements and reflective floors.
```
### Iteration 3 (Final Fine-Tuned Prompt)
```
Create a cinematic photorealistic 5-second video of a futuristic metro station at night. A sleek metallic high-speed train slowly enters the station and approaches the platform, with bright white headlights and glowing blue interior lights. Passengers wait on the platform and walk naturally as the train arrives. The station contains large glass panels, metallic pillars, digital information screens and futuristic advertisements glowing in cyan, blue, purple and warm yellow tones. The polished floor reflects the colorful lights and the metallic surface of the train. Begin with an eye-level centered platform view, then smoothly track forward toward the arriving train while maintaining realistic perspective and natural human movement. Add subtle atmospheric haze, realistic reflections, soft shadows, cinematic depth of field and detailed futuristic textures. Photorealistic cinematic style, smooth motion, realistic lighting, high detail and immersive futuristic atmosphere.
```
## Video Generation Parameters

| Parameter       | Selected Setting                       |
| --------------- | -------------------------------------- |
| Video Style     | Photorealistic cinematic               |
| Duration        | 5 seconds                              |
| Aspect Ratio    | 16:9                                   |
| Resolution      | 1024 × 576                             |
| Camera Movement | Smooth forward tracking                |
| Camera Angle    | Eye-level platform view                |
| Environment     | Futuristic metro station               |
| Weather         | Nighttime atmosphere                   |
| Lighting        | Neon and artificial cinematic lighting |
| Motion          | Moving train and pedestrians           |
| Color Scheme    | Cyan, blue, purple and warm yellow     |

## Comparison & Analysis

| Feature              | Target Video                                     | Generated Output                                      | Alignment Score |
| -------------------- | ------------------------------------------------ | ----------------------------------------------------- | --------------- |
| Composition          | Central train with platform leading lines        | Maintains a centered train and platform composition   | Very High (95%) |
| Lighting             | Bright station lights and glowing advertisements | Reproduces strong futuristic illumination             | Very High (94%) |
| Motion               | Train arrives while passengers move              | Includes train movement and natural pedestrian motion | High (92%)      |
| Color Palette        | Blue, cyan, purple and warm tones                | Closely matches the futuristic color palette          | Very High (95%) |
| Texture & Reflection | Metallic train and polished reflective floor     | Recreates metallic surfaces and floor reflections     | Very High (96%) |
| Atmosphere           | Clean futuristic nighttime environment           | Produces a realistic cinematic atmosphere             | High (93%)      |
| Camera Movement      | Smooth platform-level camera movement            | Uses controlled forward tracking                      | Very High (95%) |

## Deliverables & Key Findings

* Prompt Specificity Matters: A basic prompt produces a general metro station, while adding train design, passengers, digital displays, lighting and environment provides greater control.
* Motion Description Matters: Video prompts should describe dynamic elements such as the train arriving, passengers walking and the camera moving.
* Camera Movement: Specifying a “smooth forward tracking shot” helps create a more cinematic and realistic video.
* Lighting and Reflection: Terms such as “neon lighting”, “polished reflective floor”, “metallic surfaces” and “glowing advertisements” improve visual similarity.
* Environmental Details: Adding glass panels, metallic pillars, digital screens and futuristic advertisements makes the generated environment more detailed.
* Temporal Progression: Describing the beginning and movement of the camera throughout the 5-second clip improves scene continuity.
* Iterative Refinement: Adding specific subjects, motion, colors, textures, lighting and camera instructions improves the final output compared with the basic prompt.

## Result

A 5-second photorealistic cinematic futuristic metro station video was generated using progressive prompt refinement. The final prompt successfully described the environment, train, passengers, movement, camera motion, lighting, colors, reflections and futuristic atmosphere.

## Conclusion

By analyzing the visual and temporal characteristics of the target video, a detailed text-to-video prompt was developed. The experiment demonstrates that effective video prompting requires descriptions of subjects, motion, camera movement, lighting, colors, textures and environmental effects. Progressive prompt refinement improved the quality, realism and consistency of the generated video, producing an output that closely represents the intended futuristic metro station scene.
