<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>

<script>
  window.watsonAssistantChatOptions = {
  integrationID: "459acac2-bb03-4bc6-8061-a9f678e0b338", // The ID of this integration.
  region: "wxo-us-south", // The region your integration is hosted in.
  serviceInstanceID: "3f81b275-0f3f-43b0-bb90-1df407e1d7ba", // The ID of your service instance.
  orchestrateUIAgentExtensions: false, // If you wish to enable optional UI Agent extensions.
  onLoad: async (instance) => { await instance.render(); }
};
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>

<body></body>

</html>
