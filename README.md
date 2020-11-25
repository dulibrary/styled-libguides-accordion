# styled-libguides-accordion
Instructions to make a styled accordion out of libguides boxes.

## Example
We will recreate the accordion displayed at [Accordion Sample: Tutors](https://davenport.libguides.com/accordion).

## Insert LibGuide accordion styling
This will style the libguide boxes you will create into an accordion menu. It can be placed anywhere on your page.

1. From the LibGuides Admin page, select `Add box`
2. Title your box as `Code`
3. Select `Floating Box`
4. Click `Save`
5. Within your box, click `Add / Reorder`
6. Select `Rich Text / HTML`
7. Select the `Source` option (so you can edit the HTML directly)
8. Paste [accordion-styling](https://github.com/brianholda/styled-libguides-accordion/blob/main/accordion-styling)
9. Click `Save & Close`

## Create your boxes
These boxes will become accordion panels.

1. From the LibGuides Admin page, select `Add box`
2. Title your box
3. Select `Floating Box`
4. Click `Save`

## Add HTML to your boxes
1. Within your box, click `Add / Reorder`
2. Select `Rich Text / HTML`
3. Select the `Source` option (so you can edit the HTML directly)
4. Paste in the [new-accordion-panel](https://github.com/brianholda/styled-libguides-accordion/blob/main/new-accordion-panel) code
5. In the code:
    1. Change `#panel-name` to a unique ID name for this particular panel (e.g. `#panel-name` becomes `#technology-tutors`).
    2. Change `Panel Name` to a similar unique title (e.g. `Panel Name` becomes `Technology Tutors`).
    3. Change `id="panel-name"` to match the unique ID name you chose in step 1 (in our example, it'd be `id="technology-tutors"`).
    4. Replace `<!-- [accordion panel body content] -->` with your own code to fill in the accordion panel body (see below for an example)
6. Click `Save & Close`

## Fill in the accordion panel body content
This can be filled however you wish. Here I will give a sample we use for our tutoring accordion. This sample is just one section within the panel body (it will automatically fill up 1/3 of the box width). You can stack as many sections within the panel body as you want and they will automatically sit side-by-side or move to the next row of the panel body depending on how much room there is.

1. Replace `<!-- [accordion panel body content] -->` with [panel-section](https://github.com/brianholda/styled-libguides-accordion/blob/main/panel-section) content.
2. Modify the [panel-section](https://github.com/brianholda/styled-libguides-accordion/blob/main/panel-section) content:
    1. Replace `Panel Section` with the name of your panel section. E.g. `<!--BEGIN: Panel Section-->` becomes `<!--BEGIN: Brian Holda-->`, and `<!--END: Panel Section-->` becomes `<!--END: Brian Holda-->`
    2. Replace the `src` in `<img>` with a URL to your image (cropped to 150px by 150px)
    3. Replace `<h3>Joe Smith</h3>` with the name of your person/thing. E.g. `<h3>Joe Smith</h3>` becomes `<h3>Brian Holda</h3>`
    4. Replace `<p>Joe Smith is an I.T Professional with 27+ years of experience.</p>` with your own leading (preferrably, short) sentence. E.g. `<p>Joe Smith is an I.T Professional with 27+ years of experience.</p>` becomes `<p>Brian Holda works at Davenport University.</p>`
    5. Replace `<summary>More about Joe Smith...</summary>` with the name of your person/thing. E.g. `<summary>More about Joe Smith...</summary>` becomes `<summary>More about Brian Holda...</summary>`
    6. Replace `He's also a really nice guy.` with your own content (this can be as long or short as you wish).
    7. If you are not using a form, delete `<a class="btn btn-lg btn-primary" href="https://tutor-form.com" title="Tutor Form for Joe Smith"><i class="fa fa-envelope" aria-hidden="true"></i> Contact Joe Smith</a>`. Otherwise, if you have your own form, update the `href`, `title`, and `Contact Joe Smith` with your own information.
