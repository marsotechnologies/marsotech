# Image sources and route mapping

The retained photographs are local, optimized copies of Unsplash images. The project source record identifies them as used under the [Unsplash License](https://unsplash.com/license). The image CDN URLs below identify the original files.

| Local image | Original image URL | Current use |
| --- | --- | --- |
| `hero-team.jpg` | <https://images.unsplash.com/photo-1521737711867-e3b97375f902> | About hero; Web Application Development slider and detail hero |
| `hero-workstation.jpg` | <https://images.unsplash.com/photo-1498050108023-c5249f4df085> | Custom Software Development slider and detail hero; Services hero |
| `hero-industries.jpg` | <https://images.unsplash.com/photo-1581091226825-a6a2a5aee158> | Industries hero; Application Modernization and Maintenance slider and detail hero |
| `hero-process.jpg` | <https://images.unsplash.com/photo-1552664730-d307ca884978> | Process hero; Business Process Automation slider and detail hero |
| `hero-documents.jpg` | <https://images.unsplash.com/photo-1455390582262-044cdead277a> | Software Consulting and Technical Advisory detail hero |

The following visuals are original project illustrations authored as SVGs for local use; they do not depict clients, products, or project outcomes:

| Local image | Use |
| --- | --- |
| `hero-enterprise-systems.svg` | Homepage slider and Enterprise Application Development detail hero |
| `hero-database-foundations.svg` | Homepage slider and Database Design and Development detail hero |
| `hero-api-integrations.svg` | API Development and Integration slider and detail hero |
| `hero-cloud-architecture.svg` | Cloud-Ready Application Architecture detail hero |
| `hero-interface-design.svg` | UI/UX Design and Responsive Web Experiences detail hero |
| `hero-technology-architecture.svg` | Technologies page hero |
| `hero-portfolio-overview.svg` | Portfolio page hero; a neutral illustration, not a client deliverable |
| `hero-faq-guidance.svg` | FAQ page hero |

## Image replacements

| Page or service | Previous local image | Current local image |
| --- | --- | --- |
| Homepage API Development slider | `hero-technology.jpg` | `hero-api-integrations.svg` |
| Technologies page | `hero-technology.jpg` | `hero-technology-architecture.svg` |
| FAQ page | `hero-documents.jpg` | `hero-faq-guidance.svg` |
| Portfolio page | `hero-documents.jpg` | `hero-portfolio-overview.svg` |
| Custom Software Development detail | Reused `hero-workstation.jpg` | `hero-workstation.jpg` |
| Web Application Development detail | Reused `hero-workstation.jpg` | `hero-team.jpg` |
| Enterprise Application Development detail | Reused `hero-workstation.jpg` | `hero-enterprise-systems.svg` |
| API Development and Integration detail | Reused `hero-workstation.jpg` | `hero-api-integrations.svg` |
| Business Process Automation detail | Reused `hero-workstation.jpg` | `hero-process.jpg` |
| Database Design and Development detail | Reused `hero-workstation.jpg` | `hero-database-foundations.svg` |
| Cloud-Ready Application Architecture detail | Reused `hero-workstation.jpg` | `hero-cloud-architecture.svg` |
| Application Modernization and Maintenance detail | Reused `hero-workstation.jpg` | `hero-industries.jpg` |
| UI/UX Design and Responsive Web Experiences detail | Reused `hero-workstation.jpg` | `hero-interface-design.svg` |
| Software Consulting and Technical Advisory detail | Reused `hero-workstation.jpg` | `hero-documents.jpg` |

The service-detail image and descriptive alt text are mapped by service slug in `service-detail-page.component.ts`. Slider copy, routes, imagery, and positioning are maintained in `homeHeroSlides` in `marso-home-page.component.ts`. The first slide image is preloaded in `src/index.html`; the slider preloads only its next image.

## Images intentionally retained or not added

- The Marso logo remains unchanged in the shared header and footer.
- About, Services, Industries, and Process keep photographs that match their respective sections; they are already local and listed above.
- The Contact page uses a text-first hero and has no existing banner photograph. No stock image was added where the current design does not need one.
- Homepage service cards and portfolio project cards have no images. No stock photos or fictional product screenshots were added; portfolio details remain unpublished until genuine, approved work is available.
- Legal pages and the footer do not need decorative imagery.
