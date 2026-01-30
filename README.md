/*
 * This is a manifest file that'll be compiled into application.css, which will include all the files
 * listed below.
 *
 * Any CSS and SCSS file within this directory, lib/assets/stylesheets, vendor/assets/stylesheets,
 * or any plugin's vendor/assets/stylesheets directory can be referenced here using a relative path.
 *
 * You're free to add application-wide styles to this file and they'll appear at the bottom of the
 * compiled file so the styles you add here take precedence over styles defined in any other CSS/SCSS
 * files in this directory. Styles in this file should be added after the last require_* statement.
 * It is generally better to create a new file per style scope.
 *
 *= require_tree .
 *= require_self
 */

/* ──────────────────────────────────────────────── */
/* Your custom chatbot styles start here            */
/* Feel free to change colors, fonts, sizes etc.    */
/* ──────────────────────────────────────────────── */

body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', sans-serif;
  background: #f0f2f5;
  color: #111;
  height: 100vh;
  overflow: hidden;
}

#chat-container {
  display: flex;
  flex-direction: column;
  height: 100vh;
  max-width: 800px;
  margin: 0 auto;
  background: white;
  box-shadow: 0 0 20px rgba(0,0,0,0.1);
}

#messages {
  flex: 1;
  padding: 16px;
  overflow-y: auto;
  background: #f0f2f5;
}

.message {
  margin-bottom: 12px;
  max-width: 80%;
  padding: 10px 14px;
  border-radius: 18px;
  line-height: 1.4;
}

.user {
  align-self: flex-end;
  background: #0084ff;     /* Blue like many chat apps – or change to Pi purple #6728d6 if you prefer */
  color: white;
  margin-left: auto;
}

.bot {
  align-self: flex-start;
  background: #e5e5ea;
  color: black;
}

#input-area {
  display: flex;
  padding: 12px;
  background: white;
  border-top: 1px solid #ddd;
}

#user-input {
  flex: 1;
  padding: 12px 16px;
  border: 1px solid #ddd;
  border-radius: 24px;
  margin-right: 8px;
  font-size: 16px;
}

button {
  padding: 12px 20px;
  background: #0084ff;
  color: white;
  border: none;
  border-radius: 24px;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  background: #006edc;
}
