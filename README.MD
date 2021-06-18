<h1> Introduction</h1>
Hey There! This Script is for Developers to release the Binaries to their Respective Chats/Channels.
<br>
<br>
<h1> Steps To Follow:</h1>
<ol>
<li> Edit the <code>telegram.sh</code> file, And Paste your Bot's Token (Can be found <a href="https://t.me/BotFather">@BotFather</a>). Which is Similar to <code>123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11</code> copy that code and paste it in <code>BOT_TOKEN</code> variable.</li><br>
<li> Get Your Chat's ID, Easiest way to do so is, Add group management bot like <a href="https://t.me/DAvinash97bot">@Ava</a> and do <code>/id</code> copy that number which should look like <code>-123456789</code> it can be more digits (Depends on your Group if it is SuperGroup) and paste that Code in <code>Telegram.sh</code> in <code>CHAT_ID</code> variable. 
<pre>
    <b>It Should Now look like this</b></>
        BOT_TOKEN="123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11"
        CHAT_ID="-123456789"
</pre></li><br>
<li> Now Choose if you want to Send Message or Send Document
<pre>
<b>You Need to do like these:</b>
</>
    <b>To Send Message do</b>
        <i>sendmessage "Telegram is awesome"</i>
</>
    <b>To Send Document(s) do</b>
        <i>senddocument "file_extension(s)" "caption"</i>
        </>
        <b>Note For Document:</b>
        - Caption is Optional.</>
        - You dont need to Specify files. The extension is enough.
            >> For Example to send <code>abcd.txt</code>, You just need to pass "txt".
            >> It will also send files with similar extension "Only If exists in the same directory ofc." ;)
</pre>
</li>
<li>Now Add that bot to your Chat/Channel. Now execute the Script by <code>. ./Telegram.sh</code></li>
</ol>
