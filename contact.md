<form id="contact" action="https://spatial.support/e/" method="post">

    <div>
        <label for="name">Name</label>
    </div>
    <div>
        <input id="name" name="name" type="text" value="" placeholder="Enter your name" required>
    </div>

    <div>
        <label for="email">Email</label>
    </div>
    <div>
        <input id="email" name="email" type="text" value="" placeholder="Enter your email" required>
    </div>

    <div>
        <label for="subject">Subject</label>
    </div>
    <div>
        <input id="subject" name="subject" type="text" value="" placeholder="Enter your subject" required>
    </div>

    <div>
        <label for="message">Message</label>
    </div>
    <div>
        <textarea id="message" name="message" value="" placeholder="Enter your message" cols="21" rows="10" required></textarea>
    </div>
    
    <input type="hidden" id="returnLinkText" name="returnLinkText" value="byezy github page">
    <input type="hidden" id="returnLinkUrl" name="returnLinkUrl" value="https://byezy.github.io">
  
    <button>Send</button>
</form>
