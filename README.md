# RC Design website

Static website for Roomcreator and Design Co., Ltd. (RC Design).

## Files
- `index.html` — the page (design and behaviour). Normally you do not edit this.
- `content/site.json` — company details, headline, numbers, services, process steps.
- `content/projects.json` — projects and homes for sale.
- `img/` — photos. `img/hero.jpg` is the main photo at the top of the page.
- `.pages.yml` — settings for the editor at https://app.pagescms.org

## Editing (no code)
1. Open https://app.pagescms.org and sign in with GitHub.
2. Choose this repository.
3. "ผลงาน / บ้านขาย" = projects; "ข้อมูลบริษัทและหน้าเว็บ" = company details and page text.
4. Press Save. Cloudflare Pages publishes the change in about 1 minute.

## Photos
- JPG, landscape, about 1600 px wide, under 500 KB.
- If you replace the main photo, turn off "แสดงเส้นโครงสร้าง" (structureLines):
  the structure lines are traced for the original hero.jpg only. The X-ray effect still works on any photo.

## Contact form
The quote form currently shows a thank-you message only. To receive enquiries by email,
connect it to a form service (e.g. Web3Forms) in the submit handler near the end of index.html.
