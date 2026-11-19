<div align="center">

<h1>🎮 Discord Quest Auto-Completer</h1>

<p><b>Automatically complete active Discord quests directly from your client without downloading or playing heavy games.</b></p>

<p>
  <img src="https://img.shields.io/badge/Platform-Discord%20Desktop%20%7C%20Web-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Platform">
  <img src="https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="Language">
  <img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge" alt="License">
</p>

<br>

<a href="./Quest%20completer%20Code.txt">
  <img src="https://img.shields.io/badge/📄_OPEN_SCRIPT_CODE-Quest_completer_Code.txt-2ea44f?style=for-the-badge" alt="Get Script Code">
</a>

</div>

<hr>

<blockquote>
  <b>⚠️ IMPORTANT WARNING — USE AT YOUR OWN RISK:</b><br>
  Discord actively monitors and <b>suspends quest access</b> for accounts caught automating quest completion. Proceed at your own discretion.
</blockquote>

<blockquote>
  <b>💻 DESKTOP APP REQUIRED FOR GAME QUESTS:</b><br>
  Quests requiring you to <b>play</b> or <b>stream</b> a game will <b>NOT work in a web browser</b> or third-party wrappers (like Vesktop). You must use the official <a href="https://discord.com/download"><b>Discord Desktop App</b></a>.
</blockquote>

<hr>

<h2>📋 Supported Quest Types</h2>

<table>
  <thead>
    <tr>
      <th align="left">Quest Type</th>
      <th align="center">Desktop App</th>
      <th align="center">Web Browser</th>
      <th align="left">Action Required</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Watch Video (Desktop & Mobile)</b></td>
      <td align="center">✅ <b>Supported</b></td>
      <td align="center">✅ <b>Supported</b></td>
      <td><b>None</b> — runs automatically in the background.</td>
    </tr>
    <tr>
      <td><b>Play Game on Desktop</b></td>
      <td align="center">✅ <b>Supported</b></td>
      <td align="center">❌ <b>Unsupported</b></td>
      <td><b>None</b> — spoofs game activity automatically.</td>
    </tr>
    <tr>
      <td><b>Stream Game on Desktop</b></td>
      <td align="center">✅ <b>Supported</b></td>
      <td align="center">❌ <b>Unsupported</b></td>
      <td>Join a <b>Voice Channel with 1+ friend/alt</b> and stream any window.</td>
    </tr>
    <tr>
      <td><b>Play Activity</b></td>
      <td align="center">✅ <b>Supported</b></td>
      <td align="center">✅ <b>Supported</b></td>
      <td><b>None</b> — sends activity heartbeats automatically.</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🚀 Step-by-Step Usage Guide</h2>

<table>
  <thead>
    <tr>
      <th align="center" width="80">Step</th>
      <th align="left">Instructions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><b>1</b></td>
      <td><b>Accept a Quest:</b> Open Discord, navigate to <b>Discover &gt; Quests</b>, and click <b>Accept Quest</b> on an active quest.</td>
    </tr>
    <tr>
      <td align="center"><b>2</b></td>
      <td><b>Open DevTools:</b> Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd> (Windows/Linux) or <kbd>Cmd</kbd> + <kbd>Option</kbd> + <kbd>I</kbd> (Mac) inside Discord.</td>
    </tr>
    <tr>
      <td align="center"><b>3</b></td>
      <td><b>Switch to Console:</b> Click the <b>Console</b> tab at the top of the Developer Tools panel.</td>
    </tr>
    <tr>
      <td align="center"><b>4</b></td>
      <td>
        <b>Copy &amp; Paste the Script:</b> Open <a href="./Quest%20completer%20Code.txt"><b>Quest completer Code.txt</b></a>, copy the entire text, paste it into the Console, and press <kbd>Enter</kbd>.<br>
        <i>💡 <b>Tip:</b> If Discord blocks pasting, type <code>allow pasting</code>, press <kbd>Enter</kbd>, and paste again.</i>
      </td>
    </tr>
    <tr>
      <td align="center"><b>5</b></td>
      <td>
        <b>Follow Console Prompts:</b><br>
        • <b>Play / Watch Quests:</b> Simply wait — progress advances automatically.<br>
        • <b>Stream Quests:</b> Join a voice channel with at least one other person (or alt account) and stream any window.
      </td>
    </tr>
    <tr>
      <td align="center"><b>6</b></td>
      <td><b>Claim Your Reward:</b> Track progress via <code>Quest progress:</code> logs in the Console or the progress bar in the <b>Quests</b> tab. Once complete, click <b>Claim Reward</b>.</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>❓ Troubleshooting &amp; FAQ</h2>

<details>
  <summary><b>Nothing happens or messages stop sending after opening DevTools</b></summary>
  <p>Opening DevTools can occasionally stall Discord's network requests for a few minutes. <b>Wait a moment or restart Discord</b> and run the script again.</p>
</details>

<details>
  <summary><b>Ctrl + Shift + I does not open DevTools</b></summary>
  <p>DevTools is disabled by default on the standard Discord Stable client. Download the <a href="https://discord.com/api/downloads/distributions/app/installers/latest?channel=ptb&platform=win&arch=x64"><b>Discord PTB Client</b></a> or enable DevTools in your Discord settings file.</p>
</details>

<details>
  <summary><b>Ctrl + Shift + I takes a screenshot instead</b></summary>
  <p>This hotkey conflicts with <b>AMD Radeon Software</b>. Open your AMD Radeon settings and disable or rebind the screenshot shortcut.</p>
</details>

<details>
  <summary><b>I get a SyntaxError or Unexpected Token error</b></summary>
  <p>Ensure your browser or editor is <b>not auto-translating</b> the page when copying from <code>Quest completer Code.txt</code>. Disable translator extensions and copy again.</p>
</details>

<details>
  <summary><b>I am using Vesktop, why does it say I am on a browser?</b></summary>
  <p><b>Vesktop</b> and similar third-party clients are browser wrappers and are detected as web browsers. Use the official <b>Discord Desktop App</b> for Play/Stream quests.</p>
</details>

<details>
  <summary><b>Can I complete expired quests?</b></summary>
  <p><b>No.</b> Only active, accepted quests that have not yet expired can be completed.</p>
</details>
