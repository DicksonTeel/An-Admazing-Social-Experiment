# Welcome to an Admazing Social Experiment
I made this website for the sole purpose of containing ads to conduct an ongoing social experiment. I grew curious if there were people, in our society where anti-tracking measures are becoming more and more important, who would allow ads for perceptively moral reasons? During the lifespan of this website, all revenue gained from ads will be going towards a growing number of charities.[^donationException]

*Please be aware that this is a personal project and is currently under development at the time of this commit (April 4, 2023). I do have commitments outside of this project, so it will take an as yet undetermined amount of time to have a fully functioning site!*

In the name of transparency; all charities that receive funds and the amount of money they have received will be listed on a separate page accessible through a navigation bar at the top of the main testing screen, and the total amount of money donated will be included at the top of that page.

[^donationException]: The only exception for these donations being any money that is required to enable/sustain this site. Expectations at this time (April 4, 2023) are that less than 1% of revenue made will be kept to sustain the site.

<style>
  .button {
    border-width: 10;
    border-color: rgb(0, 0, 0);
    background-color: #ffffff;
    color: rgb(0, 0, 0);
    padding: 14px 28px;
    font-size: 16px;
    cursor: pointer;
    text-align: center;
    position: absolute;
    bottom: 10%;
    right: 10%;
  }
</style>
<input type="submit" onClick="myFunction()" value="Go to the Experiment" class="button" />
  <script>
    function myFunction() {
      window.location.href = "FirstPage.html";
    }
  </script>