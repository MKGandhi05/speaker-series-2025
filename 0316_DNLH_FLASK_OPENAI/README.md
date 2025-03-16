# 📢 Dot Net Learners House Meetup – Monthly Event - Mar 2025

# 📢 Dot Net Learners House Meetup – Monthly Event - Mar 2025

## Date Time: 16-Mar-2025 at 09:00 AM IST

## Event URL: [https://www.meetup.com/dot-net-learners-house-hyderabad/events/304750920](https://www.meetup.com/dot-net-learners-house-hyderabad/events/304750920)

## YouTube URL: [https://www.youtube.com/watch?v=rrZqYt2YDFM](https://www.youtube.com/watch?v=rrZqYt2YDFM)

![Information | 50x50](./Documentation/Images/Information.PNG)

![Seat Belt | 50x50](./Documentation/Images/SeatBelt.PNG)

Below is a demo script that Manikanta can use as a base for a 15‑minute session. He can adjust the content and add his personal touch as needed.

---

*Title: Setting the Ground – Single Turn Chat GPT Clone: The First Cut*

---

*[Introduction – 2 minutes]*

“Good morning, everyone! I’m Medishetty Manikanta Gandhi, and I’m thrilled to kick off our session today with a deep dive into building a Single Turn Chat GPT Clone – our first cut. In the next 15 minutes, I’ll walk you through the core components of our AI-powered app and explain how technologies like Flask, Azure OpenAI, React.js, Tailwind, and Auth0 come together to make this possible.

Today, we’ll cover:  
- The architecture of our app  
- How our Flask API interacts with Azure OpenAI to generate responses  
- A quick look at our frontend using React and Tailwind  
- And finally, how we secure the application using Auth0.”

---

*[Section 1: Overview of the App Architecture – 3 minutes]*

“Let’s start by understanding the architecture of our Single Turn Chat GPT Clone. At a high level, our application consists of the following layers:

![Seat Belt | 50x50](./Documentation/Images/ArchitectureDiagram.jpg)


1. *Backend API with Flask:*  
   We’re using Flask to build a lightweight API. This API handles incoming chat messages, forwards them to our language model, and then returns the generated response.  
   
2. *Azure OpenAI Service:*  
   Instead of running our own model, we integrate with Azure OpenAI. This service powers our AI by generating text completions based on user input. It provides scalability and leverages cutting-edge language models.

3. *Frontend with React.js & Tailwind CSS:*  
   Our user interface is built using React. It’s dynamic and responsive, styled using Tailwind CSS to maintain a clean and modern look.  
   
4. *Authentication with Auth0:*  
   Finally, to ensure that our app remains secure, we integrate Auth0. This handles user authentication, ensuring only authorized users can access the chat.”

(Pause briefly to allow the audience to absorb the architecture overview.)

---

*[Section 2: Deep Dive – Building the Flask API with Azure OpenAI – 5 minutes]*

“Let’s dive a bit deeper into our Flask API and see how it interacts with Azure OpenAI.

- *Flask API:*  
  We’re using Flask to expose a simple endpoint – /api/chat – which accepts a user’s prompt. When a request comes in, our API appends that prompt to a conversation context and then calls Azure OpenAI to generate a response.

- *Azure OpenAI Integration:*  
  In our API, we use the Azure OpenAI client. We pass in the conversation context, including a system prompt and the user’s input. Azure OpenAI processes the request and returns a generated text response that mimics a conversation.  
  (Here, you could share a code snippet on-screen that shows the key API call, emphasizing the parameters such as model, messages, and tokens.)

- *Real-Time Response Generation:*  
  Although our demo today may show the response as a single chunk, the idea is to eventually stream the responses in real time. This means users could see the answer as it’s being generated, enhancing interactivity.”

(Show a quick demo of the API call or code snippet if available.)

---

*[Section 3: Frontend and User Experience – 3 minutes]*

“Now, let’s talk about the frontend. Our React-based UI is designed to be intuitive and responsive. Here’s how it fits in:

- *React UI:*  
  The frontend calls our Flask API when the user submits a chat message. It then receives the AI-generated response and displays it in a chat-like interface.

- *Tailwind CSS:*  
  We’re using Tailwind CSS to rapidly style our components. This helps us maintain consistency across the UI while keeping the design modern and sleek.

- *Interaction Flow:*  
  The user types a message, clicks ‘Send’, and the React app calls our Flask endpoint. The response is then rendered dynamically. In our full version, this response will stream in real time, but today you’ll see it appear once fully generated.”

(If possible, share a screenshot or live demo of the UI at this point.)

---

*[Section 4: Securing the App with Auth0 – 2 minutes]*

“Security is a critical part of any application. We integrate Auth0 to handle user authentication. Here’s what that means for our app:

- *Auth0 Integration:*  
  Auth0 manages the login process and ensures that only authorized users can access our chat application. It handles various authentication methods, from social logins to multi-factor authentication.

- *Secure API Endpoints:*  
  With Auth0, our API endpoints are secured. This not only protects user data but also ensures that our AI service isn’t misused by unauthorized parties.

- *User Experience:*  
  While security runs in the background, the user experience remains smooth. Users log in once, and then seamlessly interact with our chat clone.”

---

*[Conclusion and Q&A – 1 minute]*

“In conclusion, today I’ve given you a high-level overview of our Single Turn Chat GPT Clone. We’ve seen how Flask, Azure OpenAI, React, Tailwind, and Auth0 combine to create a robust, secure, and engaging AI-powered chat application.

This is just the first cut – there’s a lot more to improve and iterate on. I’m excited to see how we can evolve this project further.

Thank you for your attention! I’m happy to answer any questions you might have.”

---

*End of Demo Script*

This script covers the key points for a 15‑minute session and provides a clear, structured narrative for Manikanta to build upon. Feel free to tweak or expand any section to fit his style and the audience’s needs.