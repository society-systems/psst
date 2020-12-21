<script>
    import { subscribeToNotifications, notifications } from "../store";

    let granted = window.Notification.permission === "granted";

    async function handleSubscribe() {
        try {
            await subscribeToNotifications();
            granted = true;
        } catch (e) {
            console.log(e);
        }
    }
</script>

{#if !granted}
    <section>
        <button on:click={handleSubscribe}>Enable web notifications</button>
    </section>
{/if}
