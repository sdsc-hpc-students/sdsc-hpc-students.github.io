---
layout: defaults/page
permalink: index.html
narrow: true
title: SDSC HPC Students  Projects
---

## Current Projects & Activities:

HPC Students is a program for educating and training the next generation of the High-Performance Computing workforce that focuses on educating and training students. It is designed to educate students from high school to grad school about HPC, to motivate them to pursue HPC careers, and to serve as bridge between students and HPC-related development, research and researchers. Current projects include:

* <a href="https://hpc-students.sdsc.edu/scc/index.html">Student Cluster Competition</a><br>
SCC was developed in 2007 to immerse undergraduate and high school students in high performance computing.
    Student teams must learn to design and build small cluster with support from mentors, hardware and
    software vendor partners, learn designated scientific applications, apply optimization techniques
    for their chosen architectures... <a href="https://hpc-students.sdsc.edu/scc/index.html">More...</a>

* [Cluster build-out team (Raspberry Pi and other architectures)](#pi-proj)

* <a href="https://hpc-students.sdsc.edu/hpc-training/index.html">HPC User Training</a><br>
This is an annual course, consisting of multiple sessions spread out over several weeks. Participants will learn common HPC concepts including optimization, distributed computing, cloud computing,

* [UCSD Co-Curricular Records](#sdsc-ccr)

* [SDSC Students@Supercomputing:](#students-at-sc)

* Quick-start tutorials: <a href="">UCSD Supercomputing Club activity</a>
 <hr>
 
<ul>
  <li><b> SC Student Cluster Competition Team</b><a name="scc"></a>
    SDSC supports many student activities, including the
    (<a href="http://www.studentclustercompetition.us/">http://www.studentclustercompetition.us/</a>).
    SCC was developed in 2007 to immerse undergraduate and high school students in high performance computing.
    Student teams must learn to design and build small cluster with support from mentors, hardware and
    software vendor partners, learn designated scientific applications, apply optimization techniques
    for their chosen architectures. At the SC conference, teams of 6 students compete against teams
    from all over the world, in a non-stop, 48-hour challenge to complete a real-world scientific workload,
    keep the cluster up and running, attend conference events, and demonstrate to the judges their HPC knowledge
    and skills. Acceptance to the SC competition is competitive and requires intense preparation and skill development.
    More information can be found here: <a href="https://hpc-students.sdsc.edu/scc">https://hpc-students.sdsc.edu/scc</a>.
  </li>
    <b>SDSC HPC User Training: </b><a name="hpc-training"></a> This is an annual course, consisting of multiple sessions spread out over several weeks. Participants will learn common HPC concepts including
    optimization, distributed computing, cloud computing, GPU acceleration, and parallel computing.
    Training is presented by SDSC staff and collaborators Those students who complete the HPC training will
    receive an SDSC Certificate of Completion in “HPC Training." UCSD students are eligible for CCR credit. The next session begins in January, 2021.
     More information about SDSC HPC User Training can be found <a href="https://na.eventscloud.com/website/21055/home/">here</a>.
 </li>
  <li><b>Cluster Build-out Projects: </b><a name="pi-proj"></a> Students will work together to build a 16 or 32 node PI cluster, starting in Spring Quarter, 2021. More information can be found here: <a href="https://hpc-students.sdsc.edu/pi_proj.html">https://hpc-students.sdsc.edu/pi_proj.html</a>
  </li>
 
  <li><b>UCSD Co-Curricular Records: </b><a name="sdsc-ccr"></a>
 The HPC Students Program has been working with the UCSD Co-Curricular Record team to create a system where SDSC staff and researchers can grant Co-Curricular Record credit to thier students. You can find the list of SDSC
approved CCR positions on the <a href="https://elt.ucsd.edu/ccr/ccrapprovedopportunities.html#San-Diego-Supercomputer-Center-">CCR Approved Opportunities</a> page. For more information, see: <a href="https://hpc-students.sdsc.edu/sdsc-ccr-program.html">https://hpc-students.sdsc.edu/sdsc-ccr-program.html</a>.
</li>
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
