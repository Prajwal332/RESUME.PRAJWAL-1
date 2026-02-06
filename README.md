# RESUME.PRAJWAL-1
WELCOME TO MY NEW GITHUB PAGE
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Prajwal J | Interactive Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="style.css">
</head>

<body>

<div class="resume">

    <!-- LEFT PANEL -->
    <aside class="sidebar">
        <img src="profile.jpg" alt="Profile Photo" class="profile-img">

        <h1>Prajwal J</h1>
        <p class="role">BCA Student</p>
    </aside>

    <!-- RIGHT PANEL -->
    <main class="content">

        <div class="timeline">

            <!-- PROFILE -->
            <div class="step" onclick="toggle(this)">
                <h2>Profile</h2>
                <div class="details">
                    <p>
                        Motivated BCA student with strong interest in
                        Web Development, Python programming, and
                        modern UI design. Passionate about learning
                        and building interactive applications.
                    </p>
                </div>
            </div>

            <!-- DOB -->
            <div class="step" onclick="toggle(this)">
                <h2>Date of Birth</h2>
                <div class="details">
                    <p>📅 01 January 2004</p>
                </div>
            </div>

            <!-- CONTACT -->
            <div class="step" onclick="toggle(this)">
                <h2>Contact Details</h2>
                <div class="details">
                    <p>📧 prajwal@example.com</p>
                    <p>📞 +91 XXXXXXXXXX</p>
                    <p>📍 Bangalore, India</p>
                </div>
            </div>

            <!-- SKILLS -->
            <div class="step" onclick="toggle(this)">
                <h2>Skills</h2>
                <div class="details">
                    <ul>
                        <li>HTML5, CSS3, JavaScript</li>
                        <li>Python Programming</li>
                        <li>Operating Systems</li>
                        <li>Git & GitHub</li>
                        <li>UI / UX Design</li>
                    </ul>
                </div>
            </div>

        </div>

    </main>

</div>

<script>
function toggle(step) {
    const details = step.querySelector('.details');
    if (details.style.maxHeight) {
        details.style.maxHeight = null;
    } else {
        details.style.maxHeight = details.scrollHeight + "px";
    }
}
</script>

</body>
</html>

