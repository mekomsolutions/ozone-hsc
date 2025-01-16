# Ozone HSC

**Ozone HSC** is a distribution of [Ozone HIS](https://www.ozone-his.com).

Available commands to build and run the project:
https://docs.ozone-his.com/create-distro/#available-commands

---

<p align="center">
    <a href="https://docs.ozone-his.com/"><img src="https://www.ozone-his.com/wp-content/uploads/2021/11/Ozone-Logo.png" alt="Ozone" width="30%"/></a>
</p>

<h3 align="center">Health Information System</h3>

<p align="center">
    <br/>Engage with the Ozone community and access useful resources below:
</p>

<h3 align="center">
    <a href="https://docs.ozone-his.com/">Docs</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://talk.openmrs.org/c/software/ozone-his/70">Forum</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://openmrs.slack.com/archives/C02PYQD5D0A">Chat Room</a>
</h3>

## Release Notes

<details>
  <summary><b>Version 2.0.0</b></summary>
   <ul>
    <li>Depends on:
     <ul>
      <li><a href="https://docs.ozone-his.com/users/#ozone-his-apps">Ozone Alpha 12</a></li>
      <li><a href="https://github.com/mekomsolutions/ozone-haiti?tab=readme-ov-file#ozone-haiti-">Ozone Haiti 1.0.0</a></li>
     </ul>
    </li>
   </ul>

   <b>Specific notes</b>

   <ul>
    <li>Set license to MPL 2.0.</li>
    <li>Added GitHub Action continuous integration pipeline.</li>
    <li>Set up concepts and Registration page.</li>
    <li>Configured clinical forms.</li>
    <li>Added mode of arrival form.</li>
    <li>Added emergency follow up form.</li>
    <li>Added '.ocd3.yml' file.</li>
    <li>Fixed email person attribute type uuid.</li>
    <li>Fixed capture patient photo feature.</li>
    <li>Configured Vitals and Anthropometry form to match original HSC form.</li>
    <li>Added 'dateAndTimeOfDeath' to death fields.</li>
    <li>Configured registration form with HSC form sections.</li>
    <li>Added visit attributes 'Mode of arrival' and 'Level of emergency severity assessment'.</li>
    <li>Added translation for visit attributes and update frontend config to show visit attribute fields.</li>
    <li>Ensured successful loading of configurations.</li>
    <li>Fixed logo in patient chart.</li>
    <li>Adjusted GitHub workflow to pass validation.</li>
    <li>Removed duplicate files inherited from Haiti Distro.</li>
    <li>Set Numéro Dossier as primary identifier for the patient identifier sticker.</li>
    <li>Fixed weight and height UUIDs.</li>
    <li>Added missing OpenMRS concept configs.</li>
    <li>Replaced existing drug concepts with the HSC drugs.</li>
    <li>Updated 'ozone/' to 'configs/' for serving frontend configurations.</li>
    <li>Added Odoo initializer configurations.</li>
    <li>Configured attachments-overview-widget as part of patient summary.</li>
    <li>Removed mode of arrival tag from patient banner.</li>
    <li>Disabled manual entry for 'Numero Dossier'.</li>
    <li>Configured lab order basket and results viewer widgets.</li>
    <li>Added HSC specific encounter types and privileges.</li>
    <li>Added 'allergies-details-widget' to patient summary dashboard.</li>
    <li>Moved 'Triage' from visit attributes to Vitals and Biometrics.</li>
    <li>Fixed contact and address information in patient banner.</li>
    <li>Added 'Email' to person attribute types config and fixed address translation.</li>
    <li>Fixed consultation prénatale edit privilege.</li>
    <li>Fixed missing concept 'Family History Set'.</li>
    <li>Updated material to medical supply order type.</li>
    <li>Added missing concept vacine lot number.</li>
    <li>Disabled lab reference number.</li>
    <li>Added contact person's phone number to patient banner.</li>
    <li>Adjusted count of active visits to be shown in a single page to 50.</li>
    <li>Configured locations in IPD and OPD.</li>
    <li>Added active visit obs config.</li>
    <li>Added page size and print scale config for patient identifier sticker.</li>
    <li>Moved Triage question and made optional.</li>
    <li>Added 'vitalSignsConceptSetUuid' config.</li>
    <li>Updated 'Pain Scale' to display the range as part of the label.</li>
    <li>Added config for advanced patient search app.</li>
    <li>Updated orderables for imaging and procedure order types.</li>
    <li>Added imaging and procedures order types.</li>
    <li>Added clinical form translations.</li>
    <li>Updated configuration for print identifier sticker functionality.</li>
    <li>Fixed banner app's configuration.</li>
    <li>Replaced lab order type with test order type in the order basket.</li>
    <li>Added style obs-by-encounter-widget.</li>
    <li>Moved medical supply order type to Ozone Haiti.</li>
    <li>Added labels with units for weight, height, temperature, abnominal diameter, head circumference and mid-upper arm circumference.</li>
    <li>Removed laboratory app.</li>
    <li>Added translation overrides for app navigation menu items.</li>
    <li>Added 'stock_extension' add-on and 'docker-compose-override.yml' file.</li>
  </ul>
</details>
