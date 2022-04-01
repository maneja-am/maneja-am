```php
<?php

namespace MohitAneja;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Awesome Motive Inc.',
                'position' => 'Development Team Lead',
            ],
        ];
    }

    public function getCoreSkills(): array
    {
        return [
            Php::class,
            WordPress::class,
            Laravel::class,
            Javascript::class,
            Vuejs::class,
            TailwindCss::class,
        ];
    }

    public function getOtherSkills(): array
    {
        return [
            'JavaScript / ES6',
            'jQuery / AlpineJs',
            'Responsive / HTML5 / CSS3 ReactJs / React Native',
            'NodeJS / Web & TCP Sockets Electron / NativeScript',
            'REST APIs / JSON / XML Bootstrap / Bulma / Tailwind SCSS / LESS',
            'GSAP / Anime / JS Animation Ionic / Cordova / Expo',
            'Vue Native / React Native Google APIs / Firebase',
            'Redis / Mongo DB',
            'Sketch App',
            'Adobe Photoshop',
            'Adobe Illustrator',
            'Prototyping',
            'Logo Design',
            'Website Design',
            'Mobile App Design',
            'UX Story Boards',
            'GIF Design',
            'Desktop UI/UX Design',
            'GIT / SVN',
            'Webpack / Browserify',
            'GULP / GRUNT',
            'Docker / Kubernetes',
            'Forge / Envoyer',
            'NPM / NPX / PM2 / Forever LAMP / LEMP / Server Setup Apache / NGINX',
            'AWS / Terraform / Digital Ocean',
        ];
    }

    public function isAvailableForHire(): bool
    {
        return $current_salary * 3 ?? false;
    }
}

```
