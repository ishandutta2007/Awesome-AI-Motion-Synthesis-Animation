# Awesome-AI-Motion-Synthesis-Animation

## Top AI Motion Synthesis & Animation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Text-to-Motion Generation, AI Markerless Motion Capture, Motion Retargeting, Physics-Assisted Animation & Programmatic Motion Graphics*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Motion Synthesis & Animation**. These tools synthesize 3D human and character animations from text prompts, audio, or 2D videos, extract markerless skeletal kinematics without mocap suits, apply physics-grounded secondary motion, and automate motion design workflows.



**Examples** include Move.ai, DeepMotion, Plask, RADiCAL Motion, Kinetix, Rokoko Video & Studio, Wonder Dynamics (Autodesk Flow Studio), Cascadeur, AnyWorld, and alchaincyf/huashu-motion (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for text-to-3D-motion diffusion models (`HY-Motion-1.0`, `MotionDiffuse`, `MDM`, `T2M-GPT`), monocular & multi-camera markerless mocap (`FreeMoCap`, `WHAM`, `GVHMR`, `EasyMocap`), character motion transfer (`LivePortrait`, `MimicMotion`), and motion design skills (`huashu-motion`) — ideal for 3D animators, game developers, VFX artists, and motion researchers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Move.ai](https://move.ai)**  

  Multi-camera and single-camera markerless AI motion capture platform extracting studio-grade 3D skeletal animations from standard video without suits or physical markers.



- **[DeepMotion](https://deepmotion.com)**  

  Cloud AI markerless motion synthesis suite converting 2D videos and text prompts into physics-simulated full-body, hand, and facial 3D character animations.



- **[Plask](https://plask.ai)**  

  Browser-based AI motion capture and 3D keyframe animation studio for extracting, cleaning, and retargeting video motion directly onto custom 3D rigs.



- **[RADiCAL Motion](https://radicalmotion.com)**  

  Cloud-native AI computer vision platform providing real-time, browser-based 3D human pose estimation and multiplayer motion capture from standard webcams.



- **[Kinetix](https://kinetix.tech)**  

  No-code cloud AI platform and SDK for converting videos and prompts into 3D character emotes and integrating user-generated motion into games and virtual worlds.



- **[Rokoko Studio & Rokoko Video](https://rokoko.com)**  

  All-in-one motion capture software and cloud AI video-to-mocap service supporting single/dual-camera webcam capture alongside inertial Smartsuits and Smartgloves.



- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  

  Cloud AI VFX studio that automatically captures actor motion and camera tracks from live-action footage to animate and composite CG characters into scenes.



- **[Cascadeur](https://cascadeur.com)**  

  Physics-assisted 3D keyframe animation software featuring AI-powered AutoPosing, video-to-mocap import, center-of-mass trajectory editing, and secondary motion tools.



- **[AnyWorld](https://anyworld.ai)**  

  Cloud AI 3D world and interactive character animation platform enabling rapid character rigging, motion synthesis, and real-time game asset deployment.



- **[Adobe Mixamo](https://mixamo.com)**  

  Cloud-based automatic 3D character rigging service and vast library of downloadable motion-captured animations ready for games, film, and retargeting pipelines.





## Open-Source GitHub Projects



- **[alchaincyf/huashu-motion](https://github.com)**  

  Open-source AI motion synthesis and animation skill toolkit engineered for generating structured, visually polished motion design, kinetic transitions, and animated workflows.



- **[HY-Motion 1.0 (`Tencent-Hunyuan/HY-Motion-1.0`)](https://github.com)**  

  Flagship open-source Diffusion Transformer and flow-matching model generating natural, physically plausible 3D character skeletal animations from text prompts across sports, combat, and daily actions.



- **[Human Motion Diffusion Model / MDM (`GuyTevet/motion-diffusion-model`)](https://github.com)**  

  Foundational open-source (`MIT`) text-to-motion diffusion framework synthesizing diverse, high-fidelity 3D human motion sequences and spatial trajectory edits (`PriorMDM`).



- **[MotionDiffuse (`mingyuan-zhang/MotionDiffuse`)](https://github.com)**  

  Open-source (`S-Lab`) text-driven human motion generation framework supporting multi-level text descriptions, body-part-level control, and arbitrary-length motion synthesis.



- **[T2M-GPT (`Mael-zys/T2M-GPT`)](https://github.com)**  

  Open-source (`MIT`) VQ-VAE and Generative Pre-trained Transformer architecture for generating high-accuracy 3D human motion sequences from natural-language descriptions.



- **[FreeMoCap (`freemocap/freemocap`)](https://github.com)**  

  Free, hardware-agnostic open-source (`AGPL-3.0`) multi-camera markerless motion capture system delivering research-grade 3D full-body, hand, and face tracking locally.



- **[WHAM (`yohanshin/WHAM`)](https://github.com)**  

  Open-source monocular video-to-3D human motion recovery method reconstructing globally accurate 3D trajectories and SMPL meshes in world coordinates rather than camera space.



- **[GVHMR (`zju3dv/GVHMR`)](https://github.com)**  

  Open-source monocular 3D human motion estimation model operating in a gravity-view coordinate system for stable, drift-free world-space skeletal animations.



- **[EasyMocap (`zju3dv/EasyMocap`)](https://github.com)**  

  Comprehensive open-source 3D computer vision toolbox for single/multi-person markerless motion capture and SMPL/SMPL-X/MANO parametric body recovery from RGB videos.



- **[blendi-remade/prompt2rig](https://github.com)**  

  Open-source (`Apache-2.0`) prompt-to-3D-animation pipeline that synthesizes motion clips, extracts 3D body (`GVHMR`) and 15-joint finger (`WiLoR`) kinematics locally, and exports rigged `.glb` animations.



- **[vid2anim (`mehulcode12/vid2anim`)](https://github.com)**  

  Open-source (`MIT`) AI motion capture and universal character retargeting studio with a Blender add-on supporting Mixamo, VRM, Rigify, and Unreal Engine Mannequins.



- **[Mesh2Motion (`scottpetrovic/mesh2motion-app`)](https://github.com)**  

  Free, open-source (`MIT`) browser and desktop Mixamo alternative offering automated skeletal rigging, weight painting, and 40+ pre-built animations for humans, quadrupeds, and creatures.



- **[LivePortrait (`KwaiVGI/LivePortrait`)](https://github.com)**  

  Fast, open-source (`MIT`) portrait and character facial motion synthesis engine featuring stitching and retargeting controls for expressive eyes, lips, and head movement.



- **[MimicMotion (`Tencent/MimicMotion`)](https://github.com)**  

  Open-source high-resolution human motion transfer framework using confidence-aware pose guidance to animate any character image cleanly from driving videos.



- **[Remotion (`remotion-dev/remotion`) & Motion Canvas (`motion-canvas/motion-canvas`)](https://github.com)**  

  Leading open-source TypeScript frameworks for programmatic 2D/3D motion synthesis, kinetic typography, and procedural animation rendering.



- **[Blender (`blender/blender`)](https://github.com)**  

  Flagship open-source (`GPL-2.0+`) 3D animation suite featuring Rigify modular character rigs, NLA non-linear motion blending, physics simulation, and Python automation.



### Additional Strong Open-Source Options



- **[MoMask (`EricGuo5513/momask-codes`)](https://github.com)** and **[MotionLCM (`Dai-Wenxun/MotionLCM`)](https://github.com)** for real-time latent-consistency text-to-motion synthesis and masked motion editing.

- **[BlendCap (`Arcomade/BlendCap`)](https://github.com)** and **[MaxLiu22/Motion2MixamoRig](https://github.com)** for offline single-video performance capture and automated Mixamo/Blender rig retargeting.

- **[Pose2Sim (`perfanalytics/pose2sim`)](https://github.com)** and **[OpenCap Monocular (`utahmobl/opencap-monocular`)](https://github.com)** for biomechanically validated 3D musculoskeletal kinematics from standard cameras.

- **[HumanML3D (`EricGuo5513/HumanML3D`)](https://github.com)** and **[AMASS (`nghorbani/amass`)](https://github.com)** for large-scale 3D human motion-language datasets used to train and evaluate motion synthesis models.

- **[AnimateDiff (`guoyww/AnimateDiff`)](https://github.com)** and **[Wan2.1 (`Wan-Video/Wan2.1`)](https://github.com)** for 2D/2.5D video-space motion synthesis and camera-motion LoRA animation pipelines.



**Frameworks for building custom systems**: Combine **HY-Motion 1.0 / MDM** (text-to-3D motion) or **WHAM / GVHMR / FreeMoCap** (video-to-3D mocap) with **blendi-remade/prompt2rig / vid2anim** (rig retargeting), **alchaincyf/huashu-motion** (motion design skills), and **Blender** for end-to-end open-source AI motion synthesis and animation pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
