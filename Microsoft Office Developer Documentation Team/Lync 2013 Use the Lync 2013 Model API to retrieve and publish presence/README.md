# Lync 2013: Use the Lync 2013 Model API to retrieve and publish presence
## Requires
- Visual Studio 2010
## License
- Apache License, Version 2.0
## Technologies
- Microsoft Lync 2013
## Topics
- Presence
- Lync 2013 Model API
## Updated
- 07/15/2012
## Description

<p><span style="font-size:small">The PresencePublication Lync SDK sample application uses the
<strong>BeginSignIn() </strong>and <strong>BeginSignOut()</strong> methods from the
<strong>LyncClient</strong> class to sign the user in or out of Lync. The application uses the
<strong>GetContactInformation() </strong>method of the <strong>Contact</strong> class to get information about the contact including the contact&rsquo;s current availability, name, photo, and personal note. The application uses the
<strong>ContactAvailability</strong> enumeration to set the contact&rsquo;s availability color in the application UI. Finally, the application uses the
<strong>BeginPublishContactInformation()</strong> method from the <strong>Self</strong> class to publish information about the contact.</span></p>
<p><span style="font-size:small">The Lync SDK includes three development models:</span></p>
<ul>
<li><span style="font-size:small">Lync Controls</span> </li><li><span style="font-size:small">Lync API</span> </li><li><span style="font-size:small">OCOM Unmanaged COM API</span> </li></ul>
<p><span style="font-size:small">You can drag and drop Microsoft Lync Controls into existing business applications to add Lync functions and user interface. Each Lync Control provides a specific feature like search, presence, instant messaging (IM) calls, and
 audio calls. The appearance of each control replicates the Lync UI for that feature. Use a single control or multiple controls. The programming style is primarily XAML text, but you can also use C# in the code-behind file to access the Lync API and .NET Framework.</span></p>
<p><span style="font-size:small">Use the Lync API to start and automate the Lync UI in your business application, or add Lync functionality to new or existing .NET Framework applications and suppress the Lync UI. Lync SDK UI Automation automates the Lync UI,
 and Lync Controls add separate pieces of Lync functionality and UI as XAML controls.</span></p>
<p><span style="font-size:small">Use the Lync 2010 API Reference to learn about the unmanaged Office Communicator Object Model API (OCOM). The OCOM API contains a subset of the types that are in the Lync API. You cannot start or carry on conversations with
 OCOM, but you can access a contact list and get contact presence. </span></p>
<p><span style="font-size:small">It is not recommended that you use this API, but if you are a C&#43;&#43; developer and you need to add contact and presence features to your application, then this API can work for you.</span></p>
<h1>Related content</h1>
<ul>
<li><span style="font-size:small">Lync 2010 API Reference: <a href="http://gallery.technet.microsoft.com/Lync-2010-API-Reference-48d2c5c9">
http://gallery.technet.microsoft.com/Lync-2010-API-Reference-48d2c5c9</a></span> </li><li><span style="font-size:small">Office 365 Developer Hub: <a href="http://msdn.microsoft.com/en-us/office/hh506337.aspx">
http://msdn.microsoft.com/en-us/office/hh506337.aspx</a></span> </li><li><span style="font-size:small">Lync Developer Center: <a href="http://msdn.microsoft.com/en-us/lync/gg132942.aspx">
http://msdn.microsoft.com/en-us/lync/gg132942.aspx</a></span> </li><li><span style="font-size:small">Office Developer Center: <a href="http://msdn.microsoft.com/en-us/office/aa905340.aspx">
http://msdn.microsoft.com/en-us/office/aa905340.aspx</a></span> </li></ul>
