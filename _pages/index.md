---
layout: defaults/page
permalink: index.html
narrow: true
title: SDSC HPC Students  Projects
---

## Current Projects & Activities:

HPC Students is a program for educating and training the next generation of the High-Performance Computing workforce that focuses on educating and training students. It is designed to educate students from high school to grad school about HPC, to motivate them to pursue HPC careers, and to serve as bridge between students and HPC-related development, research and researchers. Current projects include:

* <a href="https://hpc-students.sdsc.edu/scc/index.html">Student Cluster Competition:</a><br>
SCC was developed in 2007 to immerse undergraduate and high school students in high performance computing.
    Student teams must learn to design and build small cluster with support from mentors, hardware and
    software vendor partners, learn designated scientific applications, apply optimization techniques
    for their chosen architectures. <a href="https://hpc-students.sdsc.edu/scc/index.html">More...</a>

* Cluster build-out Projects:</a>
  Students will work together to build a 16 or 32 node PI cluster, starting in Spring Quarter, 2021. More information can be found here: 
    <a href="https://hpc-students.sdsc.edu/pi_proj.html">https://hpc-students.sdsc.edu/pi_proj.html</a>
(Raspberry Pi and other architectures)](#pi-proj)
    
* <a href="https://hpc-students.sdsc.edu/hpc-training/index.html">HPC User Training:</a><br>
This is an annual course, consisting of multiple sessions spread out over several weeks. Participants will learn common HPC concepts including optimization, distributed computing, cloud computing. <a href="https://hpc-students.sdsc.edu/hpc-training/index.html">More...</a>

* <a href="https://hpc-students.sdsc.edu/sdsc-ccr-program.html">SDSC/UCSD Co-Curricular Records Program:</a>
The HPC Students Program has been working with the UCSD Co-Curricular Record team to create a system where SDSC staff and researchers can grant Co-Curricular Record credit to thier students. <a href="https://hpc-students.sdsc.edu/sdsc-ccr-program.html">More...</a>

* [SDSC Students@Supercomputing:](#students-at-sc)

* Quick-start tutorials: <a href="">UCSD Supercomputing Club activity</a>
 <hr>
 
<ul>

 <li><b>SDSC Students@Supercomputing: </b><a name="students-at-sc"></a>
    One of the largest technical meetings in HPC in the world is the annual Supercomputing Conference
    (<a href="https://supercomputing.org">https://supercomputing.org</a>). SC is where experts in
    High-Performance Computing (HPC) meet. HPC spans many scientific computing domains including
    Math, Physics, Biology, and Data and Environmental Sciences. <br>
    SDSC will sponsor qualified student applications for: Student Volunteers;
    the Student Cluster Competition team; and the new #HPCImmersion Program. Get your application started today.
    More information can be found here:
    <a href="hhttps://sc21.supercomputing.org/program/studentssc/">SC Students Program.</a>
  </li>
  </ul>

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}

 {% include structure/footer.html %}
