---
layout: main
toc: Home
order: 1
title: Applicability of Hardware-Supported Containers in Low-Latency Networking
description: Alexander Daichendt, Florian Wiedner, Jonas Andre, Georg Carle
image: []
---

<article class="card">
  <header>Abstract</header>
  <div class="content">
    <p>
    Containers share the kernel with the host OS, which has implications for the network stack. Achieving connectivity between containers exclusively in software is unsuitable for reliable, low-latency applications. While extensive research has been conducted on virtual machines processing real-time traffic with hardware support, the impact of network latencies in containerized environments has received comparatively less attention. This paper analyzes throughput and network latencies in container topologies on a single host featuring single-root input/output virtualization, Linux Containers, and commercial off-the-shelf hardware. Using a state-of-the-art timestamping methodology, we measure latencies with a resolution of 1.25 us without introducing delay by the measurement methodology itself. We evaluate a single flow in a line topology with up to 64 containers. The experiments demonstrate that pinning interrupt request handlers to non-uniform memory access nodes increases throughput and decreases latencies. Furthermore, we identify dTLB misses, rescheduling interrupts, and soft interrupt floods as critical challenges as they cause spikes in latencies, and isolation is impossible. This paper contributes findings to minimize bottlenecks and limitations for real-time container applications.
    </p>
  </div>

</article>


<p class="content"> 
  This page contains the supplementary material for the paper "Applicability of Hardware-Supported Containers in Low-Latency Networking" by Alexander Daichendt, Florian Wiedner, Jonas Andre, Georg Carle. The paper is published at the 20th International Conference on Network and Service Management (CNSM'24).
</p>


<!-- <div class="accordion-box">
  <div class="accordion-box__title">
    Demo
  </div>
  <div class="accordion-box__content">
      <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.</p>
      <p>Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vu</p>
  </div>
</div> -->
