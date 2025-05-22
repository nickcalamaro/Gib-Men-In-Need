  <style>
    h1, h2 {
      margin-top: 1.5rem;
    }
    .custom-carousel-wrapper {
  width: 400px !important;  /* Force a fixed width */
  margin: 0 auto;           /* Center it */
  }

.custom-carousel-wrapper [data-twe-carousel-init] {
  width: 100% !important;   /* Ensure the carousel respects the wrapper’s width */
}
      </style>

<h1>Our Team</h1>
    
Our team is made up entirely of volunteers and are led by our trustees who are all highly experienced working in the charity sector and trained in safeguarding, conflict resolution and mental welfare.


<div class="custom-carousel-wrapper">
  {{< carousel images="/*" aspectRatio="9-13" >}}
</div>
