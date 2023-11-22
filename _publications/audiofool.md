---
title: "AudioFool: Fast, Universal and synchronization-free Cross-Domain Attack on Speech Recognition"
collection: publications
permalink: /publication/audiofool
excerpt: 'Novel Adversarial Attacks on ASR'
date: 2022-12-01
venue: 'arxiv'
paperurl: 'http://arxiv.org/abs/2309.11462'
---

This reesarch investigates the possibility of a universal adversarial attack against Automatic Speech Recognition (ASR) systems. We design the attack to be imperceptible (works even with high SNR), Universal (attack does not depend on speech content), synchronization-free (no need to time the playback), This research was part of my undergraduate research internship with the team at UCI.

Abstract
====
Automatic Speech Recognition systems have been shown to be vulnerable to adversarial attacks that manipulate the command executed on the device. Recent research has focused on exploring methods to create such attacks, however, some issues relating to Over-The-Air (OTA) attacks have not been properly addressed. In our work, we examine the needed properties of robust attacks compatible with the OTA model, and we design a method of generating attacks with arbitrary such desired properties, namely the invariance to synchronization, and the robustness to filtering: this allows a Denial-of-Service (DoS) attack against ASR systems. We achieve these characteristics by constructing attacks in a modified frequency domain through an inverse Fourier transform. We evaluate our method on standard keyword classification tasks and analyze it in OTA, and we analyze the properties of the cross-domain attacks to explain the efficiency of the approach. 
