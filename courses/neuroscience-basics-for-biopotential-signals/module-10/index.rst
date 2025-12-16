.. _neuroscience-basics-for-biopotential-signals-module-10:

Module 10 : EOG
#############################################

- **Basic Terminologies**

  1. **Electrooculography** : Technique to measure the electrical activity of the eye.
  2. **Electrooculograph** : Device to measure the electrical activity of the eye.
  3. **Electrooculogram** : Graphical representation of electrical activity of the eye.

.. todo:: Add history link of EOG 

10.1 Introduction 
**********************

Electrooculography (EOG) is a non-invasive electrophysiological technique used to record the electrical activity produced by eye movements. It is most commonly used to assess retinal function, especially the Retinal Pigment Epithelium (RPE). 

**EOG frequency range : 0.1 to 20 Hz** [1]_

10.2 Basic principle 
***********************

The basic principle of EOG is based on the fact that the human eye acts as an electric dipole where the cornea (front part of the eye) is positively charged and the retina (back part of the eye) is negatively charged. This creates a corneo retinal standing potential whose value ranges from 2mV to 10mV with a typical value of 5-6 mV in humans. 

10.3 How it works 
************************

10.3.1 Electrode placement 
====================================

In EOG, surface electrodes are placed on the skin around the eyes to capture eye movement related electrical activity in the following ways :

- **Horizontal EOG** : Electrodes are positioned at the outer canthi (corners) of both eyes to detect left & right eye movements.
- **Vertical EOG** : Electrodes are placed above and below one eye to detect up & down movements and blinks.

10.3.2 Signal Detection
=============================

The human eye acts as an electrical dipole, with the cornea being positively charged relative to the retina. When the eyes move, the orientation of this dipole changes, producing measurable voltage differences across the electrodes. These voltage changes correspond to eye movements such as saccades, smooth pursuits, and blinks and are recorded as EOG signals.

10.3.3 Signal Amplification and Filtering
================================================

EOG signals are low amplitude bioelectrical signals, typically measured in microvolts to millivolts. Therefore, they are first amplified to make them suitable for digital acquisition. Filtering is then applied to remove unwanted noise such as:

**Upside Down Labs Hardware compatible with EOG signal acquisition and processing:**

- :ref:`Neuro PlayGround Lite <neuro-play-ground-lite>`
- :ref:`Bioamp EXG Pill <bioamp-exg-pill>`

We offer our own **open source** :ref:`Chords <upsidedownlabs_software_home>` software suite, featuring tools for signal visualization, data recording (with easy save and download options), time-based plotting, and a host of other benefits-such as analyzing signal frequencies and bandpower.

10.4 Applications of EOG 
*******************************

10.4.1 Clinical applications 
======================================

1. Ophthalmology & Neurology
------------------------------------------

- Used in assessment of retinal pigment epithelium (RPE) function to detect diseases such as Best vitelliform macular dystrophy and other maculopathies. [2]_
- Used in diagnosis and monitoring of eye movement disorders such as nystagmus, saccadic abnormalities, and ocular motor nerve palsies.

2. Sleep medicine
--------------------------------

- Used for assessment of sleep disorders (such as narcolepsy, sleep apnea, parasomnias, etc.) by sleep staging as done in polysomnography to observe REM(rapid eye movement) sleep which is associated with dreaming during sleep.

10.4.2 Human-Computer interaction
=======================================

1. Marketing and Advertising 
---------------------------------------

EOG based eye tracking is used in market research to analyze consumer behavior, such as what parts of advertisements or websites capture attention.

2. Gaze Tracking 
---------------------------

EOG is a part of gaze tracking systems used in HCI to understand where a person is looking on a screen. This technology is used for creating more intuitive user interfaces and for applications in virtual reality (VR), gaming, and interactive media.

10.4.3 Assistive technology 
===================================

1. Communication Aids
---------------------------------
EOG is widely used in assistive technology for individuals with severe disabilities (e.g., locked-in syndrome). It allows them to communicate by detecting eye movements to select letters, words, or symbols on a screen.

2. Control Systems 
------------------------------------

Eye movements captured by EOG can be integrated into control systems for various devices like wheelchairs or even computers, helping people with mobility impairments.

10.4.4 Driver Monitoring in Vehicles Using Eye-Tracking 
===============================================================

It is used in automotive systems to monitor drivers attention, detect signs of fatigue or drowsiness, and assess focus levels. By analyzing eye movements, the system can identify when a driver is losing concentration or becoming tired. This information can then be integrated into vehicle safety features to provide timely alerts or adjust vehicle controls to enhance safety on the road.

Projects Using EOG
==========================

You can utilize our BioAmp Hardware to create various applications. We’ve successfully developed multiple applications, so there’s nothing holding you back from creating something innovative and outstanding. A few applications of our devices
are highlighted below:

.. grid:: 2 2 2 2
    :margin: 4 4 0 0 
    :gutter: 2

    .. grid-item-card:: Detecting UP and DOWN Movements of Eyes Using EOG
        :text-align: center
        :link: https://www.instructables.com/Tracking-UP-and-DOWN-Movements-of-Eyes-Using-EOG/

    .. grid-item-card:: Control a Servo Claw Using Your Eye Blinks (EOG)
        :text-align: center
        :link: https://www.instructables.com/Control-a-Servo-Claw-Using-Your-Eye-Blinks-EOG/

    .. grid-item-card:: Control Dino Game Using Eye Blinks (EOG)
        :text-align: center
        :link: https://www.instructables.com/Control-Dino-Game-Using-Eye-Blinks-EOG/

    .. grid-item-card:: Drowsiness Detector by Detecting EOG Signals Using BioAmp EXG Pill 
        :text-align: center
        :link: https://www.instructables.com/Drowsiness-Detector-by-Detecting-EOG-Signals-Using/

    .. grid-item-card:: Visualizing Electrical Impulses of Eyes (EOG) Using BioAmp EXG Pill
        :text-align: center
        :link: https://www.instructables.com/Visualizing-Electrical-Impulses-of-Eyes-EOG-Using-/

10.5 Advantages of EOG 
*********************************

- Non invasive & safe method
- High temporal resolution
- Can be used when eyelids are partially closed (e.g. during sleep)
- Enables hands-free control in assistive and HCI applications
- Effective for long term and continuous monitoring

10.6 Limitations of EOG 
*****************************

1. **Limited spatial precision** : EOG can tell the direction of eye movement, but it cannot accurately measure small or detailed movements of the eyes.
2. **Affected by noise and interference** : Signals can be disturbed by facial muscle movements, blinking, or electrical noise from nearby devices.
3. **Limited spatial detail** : EOG cannot show exactly where the person is looking, it only shows general eye movement (left, right, up, down).
4. **Signal drift over time** : The baseline signal may slowly shift, making long term recordings less reliable.
5. **Electrode discomfort** : Electrodes are placed around the eyes, which may feel uncomfortable, especially during long recordings.

10.7 Summary
******************

Electrooculography is a valuable non invasive technique for recording eye movements with high temporal resolution. While it is limited in spatial accuracy, it remains widely used in clinical diagnostics, sleep studies, assistive technologies, and human computer interaction due to its simplicity, safety, and robustness.

.. warning::

    **This content is provided solely for learning purposes only. Always seek medical advice from a healthcare expert for clinical application.**

10.8 References 
*********************

.. [1] `2212-0173 © 2013 The Authors. Published by Elsevier Ltd. Open access under CC BY-NC-ND license. Selection and peer-review under responsibility of the University of Kalyani, Department of Computer Science & Engineering doi: 10.1016/j.protcy.2013.12.338 <https://pdf.sciencedirectassets.com/282073/1-s2.0-S2212017313X00052/1-s2.0-S2212017313004921/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQCNyhHVGwcQJiwjZcfqB%2Fnngi0gaOG5D%2B8fV8Zrkz8AaQIhAKbrA8ondMBArQy3tLQ4kQaViOzt%2BFju4uDQxwxacezuKrIFCGAQBRoMMDU5MDAzNTQ2ODY1Igxb6t%2FB2w%2FgYSPqf5EqjwXFMLr2vTS%2FkTkJ9CaVXaTZUZm48PYa1ZxCqeGxqVR232TK61hQvyf5MYFLvESRrUzSb9OfwR1g8wV2WiulSZVMlKaaKHlsUINsy9oaI51aigdbFRzujTxvAcNARjfMDNEeUckvV6JZ7P9SA4FY2b8qA4ve7bZupQ%2FEVwUiqqUxpJkwMXaDP6G6OZAstqwqFOiJuLoYLyYFmVuVgn167Wv4%2FIwQCpncx3vaL1Opy5yf2x2QqLUBwA8TCR%2F%2F6WVBvZhNJ0%2BjzEwJ2KSsEYaG2zkrQmAiX8QGR5UAijqqRgE4Jx%2Flyds7IrAFGujbQCwadwj0PXjttPTb1w%2BbskTSjXvRWwrbvNTQaoeKuFJNeZ2HIat%2BTSKKMy4XUdOEaxaMIjkJMihbDxyeyG4yeZTn%2FXhG5E3xTfPCUhyRMDdKPxIBZ0%2FIxCB1kcXV9l0QH%2F76Kmvo5pwKyl1rMCvw%2BSB1CrBf6vNFmyQmF7vBJM2%2BvdK%2BNRdTJ1qmg5j98UC3YqQUw6THrEtuk9ZnRAZZYokWPk0rSnj%2Bl6MoAjtjTJsCktuuZavzJ22fOdnotqInecdeZVONNSeZJB8L4jzs0ScdO8UafFoJMGeJDSDb3%2FzfBvs%2Fsdbqcr7pfJqbDFwrUZjIHTfBTVqNzqMgXjsJctNEPorXsbf%2FPeE%2Furh7vkxdPGuq7P%2B2ckLcV1weoidUA0sW2gk0kKXVgW8OrpbH%2FI4kJzCz8R4i0pfAE2wsq%2FURZvk5YR2bWgsQlyxablboZytqoNfyM2wv1ezFVwWNDdYzXWt9XXl7oezVPRSqqtctiA9KtUPnOeR8eBvHXoMt8KEgIfg19iQa9c%2B%2FCBf1BsgDA6gq3SPzBIniJGzc44%2Fn3mtwMNn1g8oGOrABufwZpqmh%2B4XdLwHgeiRFVwYHvpudXCdGfJ9FhJSTnAzMpBKuUrvNopbDo8rtsl7pNXTt10WRs5o5QR3WEwEsuLpjbBBcV8xf4F17tLuPqoyM479CwirAcxKbyBDFsUM7n21COkIH3MdX4xrBHTIqa32PUhTy%2FYWuaAi9BbZSiPN4Od%2BtsjTACcsAYVCKVcYFeh2v3EhDmRvGlzjh1rHCmFro%2FMIuAfRqzAoiM4wpoeQ%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20251216T070303Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIAQ3PHCVTY4EOAB3RS%2F20251216%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=21856494202eb7a0cf284a87c4d6c3f8e1bf1fdb1678fc337265ac97a13ba838&hash=12845b144bf53cdd2f724763ae98c4e5b882a310ace09da6ba63a232f92618bc&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2212017313004921&tid=spdf-df45afbb-e47b-4276-8d9b-92ed55fde114&sid=b86afc772760a8434f09c8c344973c17a306gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=070e560601035a57&rr=9aec5195bcc80d2a&cc=in>`_
.. [2] `Creel DJ. The electrooculogram. Handb Clin Neurol. 2019;160:495-499. doi:10.1016/B978-0-444-64032-1.00033-3 <https://pubmed.ncbi.nlm.nih.gov/31277871/>`_
