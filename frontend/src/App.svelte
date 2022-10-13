<script lang="ts">
  import { instagram, linkedin } from "./constants/imgs";
  import Attendance from "./lib/Attendance.svelte";
</script>

<main>
  <div class="bg-slate-50 min-h-screen p-10">
    <h3
      class="text-center font-bold text-4xl text-teal-600 font-montserrat mb-20"
    >
      GFG Git and GitHub Workshop Attendees
    </h3>
    <Attendance />
    <h3
      class="text-center font-bold text-xl text-teal-600 font-montserrat mt-20"
    >
      by GFG Team MIT Aurangabad
    </h3>
    <div class="flex flex-row items-center justify-center mt-5">
      <a href="https://www.linkedin.com/company/gfg-students-chapter-mit/">
        <img
          src={`${linkedin}`}
          alt="Linkdin"
          height="30px"
          width="30px"
          class="mx-2"
        /></a
      >
      <a href="https://instagram.com/geeksforgeeks_mit/">
        <img
          src={`${instagram}`}
          alt="Linkdin"
          height="30px"
          width="30px"
          class="mx-2"
        /></a
      >
    </div>
  </div>
</main>
