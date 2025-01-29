<head>
 	<title>USIU Advanced Web Development Evaluation Form</title>
</head>
<body>
    <h1>USIU Advanced Web Development Evaluation Form</h1>
    <form>
        <label for="fullName">Full Name:</label><br>
        <input type="text" id="fullName" name="fullName" placeholder="Enter your full name"><br><br>

        <label for="studentID">Student ID:</label><br>
        <input type="text" id="studentID" name="studentID" placeholder="Enter your USIU Student ID"><br><br>

        <label for="email">USIU Email Address:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your USIU email"><br><br>

        <label for="github">GitHub Profile URL:</label><br>
        <input type="url" id="github" name="github" placeholder="Enter your GitHub profile URL"><br><br>

        <label for="phone">Local Phone Number (WhatsApp-enabled):</label><br>
        <input type="tel" id="phone" name="phone" placeholder="+2547XX-XXX-XXX"><br><br>

        <label for="problemSolving">1. Nairobi-Specific Problem Solving:</label><br>
        <textarea id="problemSolving" name="problemSolving" rows="4" cols="50" placeholder="Describe your API security and scalability solution for Nairobi matatu integration"></textarea><br><br>

        <label for="framework">2. Select the best JavaScript framework for real-time Nairobi news aggregation:</label><br>
        <select id="framework" name="framework">
            <option value="React.js">React.js</option>
        </select><br><br>

        <label>3. Which Laravel optimization method is best for a Nairobi e-commerce startup?</label><br>
        <input type="checkbox" id="caching" name="optimization" value="Database Caching">
        <label for="caching">Database Caching</label><br>
        <input type="checkbox" id="queues" name="optimization" value="Queues & Job Scheduling">
        <label for="queues">Queues & Job Scheduling</label><br>
        <input type="checkbox" id="scaling" name="optimization" value="Horizontal Scaling">
        <label for="scaling">Horizontal Scaling</label><br><br>

        <label for="project">4. Upload a link to a past web project (PDF/Screenshot):</label><br>
        <input type="file" id="project" name="project"><br><br>

        <label for="hosting">5. Select a Kenyan hosting provider that supports M-Pesa payments:</label><br>
        <select id="hosting" name="hosting">
            <option value="Safaricom Cloud">Safaricom Cloud</option>
        </select><br><br>

        <label for="optimization">6. How would you optimize a web app for Nairobi users on 2G/3G networks?</label><br>
        <textarea id="optimization" name="optimization" rows="4" cols="50" placeholder="Explain using PMA, lazy loading, and CDN strategies"></textarea><br><br>

        <label for="startups">7. Name two Kenyan tech startups actively hiring full-stack developers:</label><br>
        <input type="text" id="startups" name="startups" placeholder="Example: Cellulant, Twiga Foods"><br><br>

        <label for="freelancing">8. Name two Kenyan freelancing platforms for web developers besides Upwork/Fiverr:</label><br>
        <input type="text" id="freelancing" name="freelancing" placeholder="Example: Kuhustle, WorkPay Africa"><br><br>

        <input type="checkbox" id="certify" name="certify">
        <label for="certify">I certify that all responses are original and not AI-generated.</label><br><br>

        <input type="submit" value="Submit Form">
    </form>
</body>
</html>
