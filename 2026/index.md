---
layout: workshop
year: 2026
date: Workshop date 29th October 2026 (co-located with EMNLP 2026, October 24th-29th, 2026)
location: EMNLP 2026 in Budapest, Hungary
show_cfp: true

cover_image:
  image: "/assets/images/locations/5.png"
  author: Jakub Hałun
  licence_name: "CC BY-SA 4.0"
  licence_link: "https://creativecommons.org/licenses/by-sa/4.0/"

buttons:
  - text: EMNLP 2026
    url: https://2026.emnlp.org/

cfp:
  intro: |
    We invite submissions to **MINT: Multimodal Interaction in Face-to-Face Dialogue**.
    The workshop brings together researchers from **computational linguistics, NLP,
    computer vision, HCI, robotics, and cognitive science** working on multimodal
    face-to-face communication.

    We welcome work on topics including:

    - computational models that integrate verbal and non-verbal cues such as speech,
      text, gesture, facial expression, gaze, and body pose;
    - cognitive and linguistic insights about face-to-face communication that can
      inform AI systems;
    - multimodal datasets with synchronised speech, video, and motion data;
    - evaluation methods for multimodal interaction;
    - applications and tools for embodied conversational agents, social robots,
      annotation, and behavioural analysis.

    We welcome both **archival** and **non-archival** contributions. Details on submission routes, formatting, review, and presentation are provided below.

  dates:
    - event: ARR paper submission deadline
      date: May 25th, 2026
    - event: Direct paper submission deadline
      date: <del>July 8th, 2026</del> <strong>July 22nd, 2026</strong>
    - event: Pre-reviewed ARR commitment deadline
      date: <del>August 24th, 2026</del> <strong>August 31st, 2026</strong>
    - event: Notification of acceptance
      date: August 31st, 2026
    - event: Camera-ready paper due
      date: September 14th, 2026


speakers:
  - name: Judith Holler
    affiliation: Radboud University & Max Planck Institute for Psycholinguistics
    website: https://www.mpi.nl/people/holler-judith
    image: Judith.jpg
    talk:
      title: Language in face-to-face interaction
      abstract: |
        Language is a fundamentally social activity that has evolved in face-to-face interaction. In such an environment, vocal communication is embedded in a rich, visual infrastructure, where words are used together with hand gestures, facial signals, head movements and torso shifts. I will present a summary of findings from recent studies investigating language use and processing from this situated perspective to shed light on how the body contributes to meaning in face-to-face interaction. Using a combination of conversational corpus studies and experiments, we find that hand gestures and facial signals shape predictions during language processing, and that their presence influences the meaning we attribute to utterances. Together, these findings suggest that visual bodily signals have the potential to significantly impact psycholinguistic processes underpinning conversational turn-taking, and they corroborate the idea that human language is a profoundly multimodal phenomenon. As such, they are of direct relevance for designing computational models of language and social artificial agents that aim to capture naturalistic human behaviour. 
  - name: Vera Demberg
    affiliation: Saarland University & Max Planck Institute for Informatics
    website: https://www.mpi-inf.mpg.de/departments/mlp/vera-demberg
    image: Vera.jpeg
    talk:
      title: "From Motion to Meaning and back: modelling semantics in co-speech gesture"
      abstract: |
        When people speak face to face, their hands point, depict, and help organize what they say. The gestures that carry the most meaning, such as iconic, metaphoric, deictic, and discourse gestures, are also comparatively rare, far outnumbered by rhythmic beat gestures, and they often not modelled well in end-to-end gesture architectures. In this talk I argue that semantic co-speech gesture has to be supervised for explicitly. I will develop this argument through a series of recent studies from my lab. Gesture improves how language models handle discourse and turn-taking, but only once its representation captures meaning rather than kinematics alone.  Current motion tokenizers trained for reconstruction do not encode communicative content well even when reconstruction quality is high. We argue that grounding gesture in language, through natural-language descriptions of form and intent, makes it possible to retrieve and generate gestures that convey meaning, from offline synthesis to real-time embodied agents to tools that support human speakers. 

schedule_note: |
  Thursday, 29 October 2026 · All times are local Budapest time (CET, UTC+1).

  Keynotes: 30 min + 10 min Q&A · Oral presentations: 10 min + 5 min Q&A
# Titles, authors and abstracts come from _data/papers_2026.yml (by paper id).
paper_data: papers_2026
schedule:
  - start: "09:00"
    end: "09:10"
    type: opening
    title: Opening remarks

  - start: "09:10"
    end: "09:50"
    type: keynote
    speaker: Vera Demberg

  - start: "09:50"
    end: "10:35"
    type: oral
    title: Oral session 1
    talks:
      - paper: 1
      - paper: 20
      - paper: 14

  - start: "10:35"
    end: "11:00"
    type: break
    title: Coffee break
    icon: coffee

  - start: "11:00"
    end: "12:30"
    type: oral
    title: Oral session 2
    talks:
      - paper: 16
        remote: true
      - paper: 19
      - paper: 29
      - paper: 35
      - paper: 22
      - paper: 18

  - start: "12:30"
    end: "14:00"
    type: break
    title: Lunch break
    icon: utensils

  - start: "14:00"
    end: "15:30"
    type: poster
    title: Poster session
    posters:
      - paper: 2
      - paper: 5
      - paper: 9
      - paper: 15
      - paper: 30
      - paper: 31
      - paper: 33
      - paper: 34

  - start: "15:30"
    end: "16:00"
    type: break
    title: Coffee break
    icon: coffee

  - start: "16:00"
    end: "16:45"
    type: oral
    title: Oral session 3
    talks:
      - paper: 26
      - paper: 12
      - paper: 11
        remote: true

  - start: "16:45"
    end: "17:25"
    type: keynote
    speaker: Judith Holler
    remote: true

  - start: "17:25"
    end: "17:30"
    type: closing
    title: Closing remarks

organizers:
  - name: Raquel Fernández
    affiliation: University of Amsterdam
    website: https://staff.fnwi.uva.nl/r.fernandezrovira/
    image: Raquel.png
  - name: Diego Frassinelli
    affiliation: LMU Munich
    website: https://www.ling.uni-konstanz.de/en/frassinelli/diego-frassinelli/
    image: Diego.jpg
  - name: Esam Ghaleb
    affiliation: Max Planck Institute for Psycholinguistics
    website: https://esamghaleb.github.io/
    image: Esam.png 
  - name: Bulat Khaertdinov
    affiliation: Maastricht University
    website: https://www.maastrichtuniversity.nl/b-khaertdinov
    image: Bulat.jpg
  - name: Asli Ozyurek
    affiliation: Max Planck Institute for Psycholinguistics / Radboud University
    website: https://www.mpi.nl/people/ozyurek-asli
    image: Asli.jpg
  - name: Ece Takmaz
    affiliation: Utrecht University
    website: https://ecekt.github.io/
    image: Ece.jpg
  - name: Zerrin Yumak
    affiliation: Utrecht University
    website: https://www.uu.nl/staff/ZYumak
    image: Zerrin.jpg

about: |
  **MINT: Multimodal Interaction in Face-to-Face Dialogue** is a new workshop on
  modelling, generating, and understanding multimodal verbal and non-verbal
  behaviour in face-to-face communication.

  Human communication is inherently multimodal: meaning is conveyed not only
  through words and speech, but also through **prosody, gesture, facial
  expression, gaze, and body pose**. Yet much multimodal NLP still treats these
  signals as peripheral context or as outputs generated only after linguistic
  content has already been decided. MINT addresses this gap by focusing on
  multimodal interaction as a core part of communication.

  The workshop aims to bring together researchers across **computational
  linguistics, NLP, computer vision, cognitive science, HCI, and robotics** to
  study the resources, modelling approaches, processing methods, and evaluation
  strategies needed for face-to-face dialogue.

  We are particularly interested in work that connects insights about **human
  multimodal communication** with the development of **AI systems that interact
  with humans or simulate human-like behaviour**. This includes research on new
  datasets, multimodal learning methods, embodied agents, social robots, and
  evaluation frameworks for naturalistic interaction.

news:
  - content: 'The <a href="#schedule">workshop program</a> is now online, including the keynote talks by Vera Demberg and Judith Holler.'
    date: 2026-10-13

  - content: Direct paper submission deadline has been extended to July 22nd, 2026. The commitment deadline for pre-reviewed ARR papers is August 24th, 2026.
    date: 2026-07-02
    
  - content: Call for papers is now out!
    date: 2026-03-20
    url: https://mintworkshop.github.io/cfp/
  - content: MINT has been accepted as a workshop at EMNLP 2026.
    date: 2026-02-20
    url: https://2026.emnlp.org/

  
sponsors:
  - name: Max Planck Institute for Psycholinguistics
    url: https://www.mpi.nl
    image: MPI.png

program_committee:
  - name: Justine Cassell
    affiliation: INRIA & École Polytechnique
  - name: Kerstin Fischer
    affiliation: University of Southern Denmark
  - name: Rada Mihalcea
    affiliation: University of Michigan
  - name: Patrizia Paggio
    affiliation: University of Malta
  - name: Catherine Pelachaud
    affiliation: Sorbonne University
  - name: Hayley Hung
    affiliation: TU Delft
  - name: Gabriel Skantze
    affiliation: KTH Royal Institute of Technology
  - name: David Schlangen
    affiliation: University of Potsdam
  - name: Taras Kucherenko
    affiliation: Electronic Arts
  - name: Petra Wagner
    affiliation: Bielefeld University
  - name: Dirk Heylen
    affiliation: University of Twente
  - name: Pat Healey
    affiliation: Queen Mary University of London
  - name: Hendrik Buschmeier
    affiliation: Bielefeld University
  - name: Casey Kennington
    affiliation: Boise State University
  - name: Rachel McDonnell
    affiliation: Trinity College Dublin
  - name: Stefan Kopp
    affiliation: Bielefeld University
  - name: Ruben Janssens
    affiliation: Ghent University
  - name: Ilya Burenko
    affiliation: TU Dresden
  - name: Martijn Vastenburg
    affiliation: Radboud University
  - name: Chinmaya Mishra
    affiliation: Max Planck Institute for Psycholinguistics
---
