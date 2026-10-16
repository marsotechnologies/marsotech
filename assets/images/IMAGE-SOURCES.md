Hero photos are downloaded and optimized from Unsplash. They are used under the Unsplash License.

- hero-team.jpg: https://images.unsplash.com/photo-1521737711867-e3b97375f902
- hero-workstation.jpg: https://images.unsplash.com/photo-1498050108023-c5249f4df085
- hero-industries.jpg: https://images.unsplash.com/photo-1581091226825-a6a2a5aee158
- hero-technology.jpg: https://images.unsplash.com/photo-1518770660439-4636190af475
- hero-process.jpg: https://images.unsplash.com/photo-1552664730-d307ca884978
- hero-documents.jpg: https://images.unsplash.com/photo-1455390582262-044cdead277a

The homepage service slider reuses these optimized, licensed images:

- Custom Software Development: hero-workstation.jpg
- Web Application Development: hero-team.jpg
- API Development and Integration: hero-technology.jpg
- Business Process Automation: hero-process.jpg
- Application Modernization and Maintenance: hero-industries.jpg
- Enterprise Application Development: hero-enterprise-systems.svg (original custom vector illustration, created for this project)
- Database Design and Development: hero-database-foundations.svg (original custom vector illustration, created for this project)

The initial slide image is preloaded in `src/index.html`; the slider preloads only the next slide image to avoid eagerly downloading the full image set.

Homepage slider copy, service routes, image mapping, and image positioning are maintained together in `homeHeroSlides` in `src/app/features/home/marso-home-page.component.ts`. Change `slideDuration` in the component to adjust the autoplay interval. Image crossfades and text entrance timing are controlled by the slider keyframes in that component's styles.