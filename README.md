`hot-user-message-toasts`

Simple, tiny widget that will listen to user-message-success, user-message-info and user-message-error and will display a paper-toast with the message.

Each event type has a different paper toast assigned to it. Each paper toast is themable with a mixin.
Because of the nature of the toasts, this widget should be higher up in your DOM.

In your index.html you might have:

    <hot-user-message-toasts>
      <my-app></my-app>
    </hot-user-message-toasts>

