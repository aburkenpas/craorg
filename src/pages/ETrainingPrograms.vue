<template>
  <Layout>
    <PageHeader title="CRA’s E-Training Programs" />
    <Page>
      <p>All of CRA’s E-Programs are presented live and in an interactive format, through Zoom or any video conferencing platform that the client prefers. We are flexible and can adjust the programs, the timing, and the content to the specific needs of the client.</p>
      <ol>
        <li><b>Threat Management Team Training</b> (6+ hrs. in three 2-hour segments) This is our most comprehensive program delivered to the company’s interdisciplinary Threat Management Team as their initial training program or as a refresher program.</li>
        <li style="padding-top: 40px; padding-bottom: 40px;"><b>Preventing and Managing Workplace Violence – a program for “Critical Personnel”</b> This is a program for Human Resource Managers, Corporate Security, Upper Level Management, Corporate Counsel, and other “critical personnel” to provide a general understanding of the fundamentals of workplace violence prevention and management that is consistent with the level of responsibilities of the attendees. (generally 1.5 - 3 hrs. depending on time availability)</li>
        <li><b>Employee and Manager Awareness Program</b> – this is generally best presented on a regular basis through use of our purchased <a href="http://craorg.com/training-materials/">video program</a>, which can be delivered in a variety of ways, including through the company’s existing online training portal. CRA’s Employee Awareness Program is less than 12 minutes long, with an additional (and optional) section for managers/supervisors, along with an additional (and optional) program of how to respond to situations involving an “Active Shooter”. However, if live training is preferred, we can present this either separately or in conjunction with our video.</li>
        <li style="padding-top: 40px;"><b>Specific Topics/Target Audiences</b> (generally 1-3 hours, but this can vary, depending on the subject and time availability)
          <ol style="list-style-type: lower-alpha; padding-top: 10px; padding-bottom: 20px;">
            <li>Safe Terminations &amp; Layoffs</li>
            <li>De-escalating Angry Employees</li>
            <li>Leadership Team Presentation </li>
            <li>Security Manager Training</li>
            <li>Train-the-Trainer: for those who are presenting workplace violence awareness programs to employees and managers</li>
          </ol>
        </li>
      </ol>
      
    </Page>
  </Layout>
</template>

<script>
import PageHeader from "~/components/PageHeader.vue";
import Page from "~/components/Page.vue";

export default {
  components: {
    PageHeader,
    Page
  }
};
</script>

<style lang="scss" scoped>
.copy-content h2 {
  margin: 3rem 0;
}

.sub-nav {
  text-align: center;
  background: $concrete;
  padding: 3rem;

  a {
    color: $mine-shaft;
    font-size: 2.2rem;
    font-weight: bold;
  }
}
h2 {
  font-weight: 900;
}
</style>