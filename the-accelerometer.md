### Measuring Acceleration

In this class we will measure acceleration in two different ways using the IOLab device. In the first method we use the wheel sensor. The wheel sensor really measures the position as a function of time. The software can then easily deduced the rate of change of position as a function of time (velocity) and the rate of change of velocity as function of time, the acceleration. 

### The accelerometer in smartphones and the IOlab

The accelerometer is a tiny microelectromechanical system (acronym is MEMS, see figure). It is essentially a mass on a spring but microscopic masses and springs. The spring compression/extension lead to tiny change in electrical output that can be amplified and measured. 

[ciscode|rev=1|tool=elmsmedia|item=4246|entity_type=node|render=display_mode|display_mode=mediasvg__right__small__lightboxed]

The accelerometer and the gyroscope (to be discussed later) are two of the most important MEMS. They are used in phones to determine direction and detect motion. Because smartphones are now mass produced, the accelerometer is a fairly affordable electronic component and your IOLab is equipped with one. 

What does the accelerometer measure? If you put your calibrated IOLab on a flat horizontal surface with z axis pointing up, it should measure <lrn-math>a_z = 9.80\; m/s^2</lrn-math>. How can that be? The IOLab clearly is not moving, so it should have zero velocity and zero acceleration.

If on the other hand you throw the IOLab in the air while recording, you will notice that all 3 components of acceleration suddenly drop to zero. But isn't that supposed to be free fall with an acceleration of <lrn-math>a_y = - 9.80\; m/s^2</lrn-math>?

The accelerometer does not measure standard acceleration, it actually measures something called "proper acceleration" which is a concept from Einstein’s theory of gravity: General Relativity! As you might guess, a complete description of this concept is much beyond this course.  But you may be familiar with some aspects already.  In engineering, proper acceleration is often called the g-force. This is technically a misnomer since it is not a force but the basic idea is that the accelerometer measured the acceleration that you “feel”. 

An observer in free-fall in space with no air resistance feels nothing; this is zero-g. An observer on Earth feels an upward push by the floor with a proper acceleration of 1 g.  Compared to somebody in free-fall we are accelerating upward with an acceleration equal to <lrn-math>g = 9.80\; m/s^2</lrn-math>. We are so used to it, we don’t think of it as a push but it is. Pilots are usually trained to sustain acceleration of up to 9-g for extended times.   

In this course, we will use the standard definition of acceleration (what we have defined up to now) not proper acceleration.  Therefore, we will sometimes need to subtract the 1-g upward acceleration that the accelerometer measures when at rest. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
In lab 2 (and many other situations), we will often look at motion on a horizontal surface. If we only care about acceleration in the horizontal direction , we do not need to subtract g. In a horizontal direction, the accelerometer measures the same thing that the wheel sensor measure.
</lrndesign-sidenote>



