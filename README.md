## Abstract

Building a complete inertial navigation system using the limited quality data provided by current smartphones has been regarded challenging, if not impossible. This paper shows that by careful crafting and accounting for the weak information in the sensor samples, smartphones are capable of pure inertial navigation. We present a probabilistic approach for orientation and use-case free inertial odometry, which is based on double-integrating rotated accelerations. The strength of the model is in learning additive and multiplicative IMU biases online. We are able to track the phone position, velocity, and pose in real-time and in a computationally lightweight fashion by solving the inference with an extended Kalman filter. The information fusion is completed with zero-velocity updates (if the phone remains stationary), altitude correction from barometric pressure readings (if available), and pseudo-updates constraining the momentary speed. We demonstrate our approach using an iPad and iPhone in several indoor dead-reckoning applications and in a measurement tool setup.

## Paper and presentation

[arXiv pre-print](https://arxiv.org/abs/1703.00154)

[Presentation slides]({{ site.baseurl }}/assets/presentation.pdf)

## Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/L-E9fNsrvII" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>

## Referencing

{% raw  %}
```
@inproceedings{Solin+Cortes+Rahtu+Kannala:2018,
      title = {Inertial Odometry on Handheld Smartphones},
     author = {Solin, Arno and Cortes, Santiago and Rahtu, Esa 
               and Kannala, Juho},
       year = {2018},
  booktitle = {Proceedings of the International Conference on 
               Information Fusion (FUSION)}
}
```
{% endraw  %}
