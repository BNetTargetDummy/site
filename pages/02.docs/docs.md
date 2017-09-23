---
title: Docs
typed:
    pretext: 'root@localhost: ~$'
    options:
        strings:
            - 'td request wow character -r maelstrom -c jareff'
            - 'td store -i 1000100'
        typeSpeed: 100
        startDeplay: 0
        backSpeed: 50
        backDelay: 1000
        smartBackspace: false
        shuffle: true
        fadeOut: false
        fadeOutClass: 'typed-fade-out'''
        fadeOutDelay: 500
        loop: true
        loopCount: Infinity
        show_cursor: true
        cursor_char: █
        content_type: html
        backDely: false
groups:
    -
        name: Application
    -
        name: Console
        parents:
            -
                name: 'How to Use'
                image_width: 300
                image_height: 150
                path: /docs/console
    -
        name: Logger
    -
        name: Documentation
        parents:
            -
                name: 'Getting Started'
                image_width: 300
                image_height: 150
                path: /docs/documentation/getting-started
navs:
    -
        name: Console
        path: /docs/console
        options:
            -
                depth: 1
                type: link
            -
                depth: 2
                type: id
    -
        name: Documentation
        path: /docs/documentation/getting-started
        options:
            -
                depth: 1
                type: link
            -
                depth: 2
                type: id
---

