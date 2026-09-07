# Your Name — Personal Blog

A minimal Jekyll blog with Decap CMS, ready for Netlify.

## Set it up without code

1. **Create a GitHub repository.** Create a new repository on GitHub, then upload all of these files while keeping the folder structure unchanged.
2. **Connect it to Netlify.** In Netlify, choose **Add new site → Import an existing project**, select GitHub, and choose this repository. Netlify will use the included build settings automatically.
3. **Enable the CMS login.** In Netlify, open **Project configuration → Identity** and enable Netlify Identity. Under **Identity → Services**, enable **Git Gateway**. Invite yourself under **Identity → Invite users**.
4. **Open the content manager.** Visit `https://your-site.netlify.app/admin` and log in with the invited account. Choose **Articles → New Article** to publish your first post.
5. **Personalize the site.** Replace `Your Name` and `Advertising Measurement` in `_config.yml`, replace the LinkedIn address there, and add your profile photo at `assets/images/profile.jpg`. Keep the filename the same, or update the image path in `_config.yml`.

## Local preview

If you have Ruby and Bundler installed, run `bundle install` once and then `bundle exec jekyll serve`. The site will be available at the local address Jekyll prints.

## Notes

- Posts are stored in `_posts` and are created through the CMS.
- Uploaded images are stored in `assets/images/uploads`.
- The site includes a sitemap, robots file, canonical tags, social sharing metadata, and structured data automatically.
- Update `url` in `_config.yml` to your final public site address for fully accurate sitemap and canonical URLs.
