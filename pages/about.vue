<!--

Edit this file within the <template> tags to change the About tab

-->
<template>
  <div class="about text-left">
    <p>
      <img src="/logo.svg" alt="ETAG logo" style="height: 150px;">
    </p>
    <p>
      <h2>Electronic Transponder Analysis Gateway</h2>
      The Electronic Transponder Analysis Gateway (ETAG) is a database and software system to provide professional
      data management and versatile data dissemination to the growing community of researchers who use Radio Frequency
      Identification (RFID) technology to advance biological inquiries in fields like animal behavior, ecological
      physiology, and community ecology. ETAG is an infrastructure based on open-source tools, allowing scientists to
      collect, validate, visualize, analyze, and share data in near real-time. ETAG facilitates new capacities both for
      producing novel science and for sharing data with fellow researchers and the general public.  Our system will free
      up time from the management of data collection, analysis, and curation (currently done by hand), leaving
      researchers with more time for science.
    </p>
    <p>
      <h3>About RFID</h3>
      RFID is a mature and ubiquitous technology, familiar to people in the form of electronic tool-booths or as
      'microchip' tags implanted in cats and dogs. RFID entails short-range wireless communication between small
      transponder tags and readers, and it can facilitate tracking of individual items or animals that are equipped with
      a tag. A community of researchers has emerged that employs RFID to track individual birds, mammals, fish,
      reptiles, and even insects in a wide range of field and laboratory research endeavors.
    </p>
    <p>
      <h3>Getting Started with ETAG</h3>
      Please visit our  <a href="https://osf.io/eqxt5/">User Guide</a> to get started using ETAG.
    </p>
  </div>
</template>

<script>
  export default {
    auth: false  // this page does not require authentication to view
  }
</script>
