<style>
.footer-wrapper {
    display: flex;
    width: 100%;
    background: var(--vp-c-bg);
    border-top: 1px solid var(--vp-c-bg-alt);
    z-index: 26;
    background: linear-gradient(to bottom, var(--vp-c-bg) 25%, #0f0e19);
}

.footer {
    display: flex;
    justify-items: center;
    flex-direction: column;
    text-align: justify;
    max-width: calc(var(--vp-layout-max-width) - 64px);
    margin: 0 auto;
    font-size: 12px;
    color: #9ba2a9;
    padding: 6em 9em;
}

.footer a {
    color: #fff;
}
</style>

<template>
    <div class="footer-wrapper">
        <div class="footer">
            <p>
                IMPORTANT: Participating in AtomOne requires sharing only your public keys, NOT your private keys. In
                connection with AtomOne, you should never be asked to share your private key or any seed or recovery
                phrase. This means that you should never be contacted by email, phone call, or other form of messaging,
                nor receive instructions or a request to share your private key or seed or recovery phrase. Any request
                for your private key or seed or recovery phrase should alert you immediately to potential fraud. Beware
                of bad actors who seek to obtain access to your wallet or digital identity. Keeping your private key and
                seed or recovery phrases secure is critically important, and failure to do so could result in theft of
                your digital identity and loss of whatever you may own, including digital assets, that are associated
                with your digital identity. Certain statements included on this website (or in any linked materials) are
                forward-looking statements. Please visit the <a href="https://atom.one/terms/">Terms of Service</a> page
                for further details about eligibility and your usage of the AtomOne website.
            </p>
            <br />
            <p>
                DISCLAIMER: Nothing on this website is, and nothing on this website is intended to be, an offer of
                tokens or securities.
            </p>
            <br />
            <p>
                This website is a community-owned and operated resource, created and maintained by All in Bits (AiB), a
                contributing member of the AtomOne ecosystem. It is not an official website of AtomOne, and the
                information contained within does not represent the official views, decisions, or governance of the
                AtomOne community or its DAOs. The content and opinions expressed herein are those of the AiB. Use of
                this website is at your own discretion, and no guarantees are made regarding the accuracy, completeness,
                or reliability of the information provided.
            </p>
        </div>
    </div>
</template>
