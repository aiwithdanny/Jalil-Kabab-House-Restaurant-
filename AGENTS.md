<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Keep the restaurant as a single scrolling index route with section anchors, as explicitly requested; all share metadata belongs on that leaf route.
- Keep menu and review content in a browser-safe data module so presentation and validation remain independent.
- Reservations are validated client-side and handed to WhatsApp for the customer to send; never claim a booking was stored or confirmed automatically.
- Define all visual roles and responsive layouts in the global token-driven design system; reuse the shared Button for interactive controls.
