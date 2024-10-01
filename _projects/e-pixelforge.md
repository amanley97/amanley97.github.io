---
layout: page
title: PixelForge
description: AI enhanced image editing on the go!
img: assets/img/redhat/openshift.png
importance: 2
category: extracurricular
related_publications: false
---

PixelForge is a cutting-edge prototype that enables on-the-go image editing powered by AI/ML models. It utilizes an ESP32 camera, which is remotely linked to Dropbox via an API, automatically storing each captured image. OpenShiftAI then retrieves the image data from Dropbox using an access token. From there, users can seamlessly apply one of three available stylization models to transform their images.

**Role:** Cloud Leader - Utilized the RedHat OpenShift Software to develop the cloud interface and AI model integration.

> See my [write-up](/blog/2024/redhat-openshift) on the OpenShift Platform here.

**Technologies used:**
* ESP-32 CAM (Image Capture)
* Dropbox [API](https://www.dropbox.com/developers/documentation/http/documentation)
* RedHat OpenShift Cloud Platform
* Intel AMX Hardware Acceleration
* Fast Neural Style Transfer [Models](https://github.com/onnx/models/tree/main/validated/vision/style_transfer/fast_neural_style)

**Skills:** Python Programming, C Programming, Cloud Infrastructure, TensorFlow, PyTorch

All the project [code](https://github.com/amanley97/hackmidwest2024) is fully open-source!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/redhat/redhat-outer-loop.png" title="Project Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Preview of the Frontend after Deployment!
</div>

**Video Demo:** Checkout or sleep-deprived [walkthrough](https://youtu.be/rLVVBiGwtHc?si=4gcOujqafBb1uldZ) of the system!