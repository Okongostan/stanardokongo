<!DOCTYPE html>

                <li><a href="#" onclick="showSection('home')">Home</a></li>
                <li><a href="#" onclick="showSection('about')">About Me</a></li>
                <li><a href="#" onclick="showSection('contact')">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home" class="home active">
            <h1>Welcome</h1>
            <p>Hello! I am Okong'o Stanard, a student at KCA University. Am currently studing for IT.</p>
        </section>
        <section id="about" class="about">
            <h1>About Me</h1>
            <p>Hi, I'm Okong'o Stanard. I am currently studing IT.I am a teacher by proffesional</p>
        </section>
        <section id="contact" class="contact">
            <h1>Contact Me</h1>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024. All rights reserved.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            document.querySelectorAll('section').forEach(section => {
                section.classList.remove('active');
            });
            document.getElementById(sectionId).classList.add('active');
        }
    </script>
</body>
</html>
# stanardokongo
