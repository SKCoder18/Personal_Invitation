# Personal Invitation

Standalone personal invitation link generator. No dependencies, database, or build step.

## Deploy on Vercel
Import SKCoder18/Personal_Invitation. Select framework **Other**, leave the build command empty, and use the repository root as the output directory.

## Use
Enter a guest or family name, select Bride’s side (Vummadi Vari) or Groom’s side (Mukkara Vari), select English or Telugu, click Generate link, then copy the link. Open invitation previews the wedding website, not this generator.

Links point to https://wedding-invitation-blond-six.vercel.app/ with guest, lang and side query parameters. The wedding website must publish its personalization update before names appear there. This repository does not deploy or modify the wedding website.

To change the wedding destination, edit the live URL in index.html.

Names are processed in your browser and are not stored in a database. Names appear in generated URLs; forwarded links retain that name. This generator is public and has no login.

## Local preview
Open index.html in a browser. If clipboard access is unavailable, the tool selects the link for manual copying.
