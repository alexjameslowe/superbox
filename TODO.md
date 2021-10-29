## 1: Document: using al classes with fa icons.

@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css?ver=5.7.2');
     
    <div class="sb sb-boxes footer-socmed-icons">
    <i class="sb fa fa-facebook-square"></i>
    <i class="sb fa fa-twitter"></i>
    <i class="sb fa fa-linkedin"></i>
</div>



## 2: Width of vertical elements
I have this message that I want to appear in the center of a gallery. The message has three vertical elements. 
I want the first one to define the width of the element, and I want the rest to respond to it. That's the problem. I can't do that easily.

<template>
  <div class="sb sb-spread sb-boxes sb-content-center">
    <div class="sb sb-boxes sb-greedy-1" style="width:400px;">
      <div class="sb sb-explicit" style="width:12px; background:#0C7797"></div>
      <div class="sb sb-greedy sb-vertical" style="background:rgba(255, 255, 255, 0.5);">
        <div class="sb" style="white-space:nowrap;">I want this one to define the width of the message</div>
        <h1 class="sb">HEY This is longer text whats going on here</h1>
        <div class="sb">Testing ABC</div>
      </div>
    </div>
  </div>
</template>


