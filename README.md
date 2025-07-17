# Collaborative-Timeline-Builder

This HTML file contains a complete, self-contained collaborative timeline builder.

Key Features:

Real-time Synchronization: Uses Firestore's onSnapshot to update the timeline in real-time across all connected users.

Authentication: Automatically signs in users anonymously or with a provided custom token (__initial_auth_token). Displays the user's unique ID.

Drag-and-Drop: Allows users to reorder timeline items directly on the page, with changes saved to Firestore.

CRUD Operations:

Create: Add new timeline events with a title, date, and description.

Read: Displays all timeline events, sorted by their order.

Update: Edit existing event details (title, date, description) via a modal.

Delete: Remove events from the timeline.

Comments: Each timeline item can have multiple comments, which are also synchronized in real-time.

Markdown Support: Descriptions and comments are displayed using <pre> tags to preserve basic Markdown-like formatting (line breaks, spaces).

Export: Users can export the entire timeline data as a JSON file.

Responsive Design: Styled with Tailwind CSS for a clean look that adapts to different screen sizes.

Loading Indicator & Message Box: Provides visual feedback during data loading and for user actions (e.g., success/error messages).

To use this application:

Save the code as index.html.

Open the index.html file in a web browser.

You can then start adding timeline events, reordering them, and adding comments. Any changes you make will be reflected in real-time for anyone else viewing the same application instance.
