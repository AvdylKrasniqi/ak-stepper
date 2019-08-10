# ak-stepper
ak-stepper is a stepper plugin built with pureJS.
It is built on pure js, so no jquery or similiar scripts are needed.
<h3>Demo</h3>
<a href="https://avdylkrasniqi.github.io/ak-stepper/">Demo</a><br/>
<b><i>This code isn't written by me. I borrowed it from w3schools and I have updated it</i></b>
<b>External links used</b>
<ul>
  <li>FontAwesome</li>
  <li>Argon - A theme based on bootstrap 4</li>
</ul>
<h1> Install & Implement</h1>
<p> Download the project, and add <code>ak-stepper.css</code> and <code>ak-stepper.js</code> on your html file</p> 

<h1> Setup</h1>
<p> Add this javascript line in the end of body tag</p>
<code><script type="text/javascript">
  var currentTab = 0;
  showTab(currentTab);
  </script>
</code>

<h1> How to use</h1>
  <h2>Create a tab</h2>
  <p>You can easily add a new step just by creating a div that have "tab" class, then the js will automatically render the steps.
  <h2>Configure steps (Changing icons and step description)</h2>
  <p>To set an icon or a description of the step, there are datasets `data-akstepper-iconclass` and `data-akstepper-desc`</p>
  <p>Simply, just put the classes of icon (from Fontawesome or similar) on `data-akstepper-iconclass`, and a description on `data-akstepper-desc`</p>
  <h2>Configure inputs</h2>
  <p>If you want to make an input optional, just put the `data-akstepper-optional` attribute on desired input</p>
