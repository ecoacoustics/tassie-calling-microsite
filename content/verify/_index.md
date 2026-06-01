+++
title = "Can you hear a Forty-spotted Pardalote?"
+++

<oe-verification-grid data-campaign="Forty-spotted Pardalote" id="verification-grid" grid-size="1">
    <!-- Insert a template element to give non-default attibutes to the spectrogram, example below. 
    https://oe-web-components.netlify.app/examples/create-verification-grid/ --> 
    <!-- <template>
        <div class="tile-spacing">
            <oe-subject-tag></oe-subject-tag>
            <oe-media-controls for="spectrogram"></oe-media-controls>
        </div>
        <oe-axes>
        <oe-indicator>
            <oe-spectrogram id="spectrogram" mel-scale></oe-spectrogram>
        </oe-indicator>
        </oe-axes>
        <div class="tile-block">
            <oe-task-meter></oe-task-meter>
        </div>
    </template> -->
    <oe-verification verified="true" shortcut="y">Yes</oe-verification>
    <oe-verification verified="false" shortcut="n">No</oe-verification>
    <oe-verification verified="unsure" shortcut="u">Unsure</oe-verification>
    <oe-data-source
        slot="data-source"
        for="verification-grid"
        allow-downloads="false"
    ></oe-data-source>
</oe-verification-grid>

<p class='examples-link'><a href="/verify/example-calls/" target="_blank" rel="noopener">Example Calls</a></p>

<style>
    .examples-link {
        margin-block: var(--micro-padding-large);
        text-align: center;
        font-size: 1.5em;
    }
</style>