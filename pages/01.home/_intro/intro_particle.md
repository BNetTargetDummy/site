---
title: Intro
section:
    shade: light
secti0n:
    pallet: inherit
particlejs:
    options:
        particles:
            number:
                value: 125
                density: { enable: true, value_area: 800 }
            color:
                value: ['#00b4ff', '#aa73ff', '#83d238', '#33b1f8']
                0: [{ value: '#00b4ff' }]
                1: { 1: { value: '#aa73ff' } }
                2: { 2: { value: '#f8c210' } }
                3: { 3: { value: '#83d238' } }
            shape:
                type: circle
                stroke: { width: 0, color: '#00b4ff' }
                polygon: { nb_sides: 5 }
                image: { width: 100, height: 100 }
            opacity:
                value: 0.5
                random: false
                anim: { enable: false, speed: 1, opacity_min: 0.1, sync: false }
            size:
                value: 3
                random: false
                anim: { enable: false, speed: 3, size_min: 0.1, sync: true }
            line_linked:
                enable: true
                distance: 125
                color: '#00b4ff'
                opacity: 0.4
                width: 2
            move:
                enable: true
                speed: 0.5
                direction: none
                random: false
                straight: false
                out_mode: out
                bounce: false
                attract: { enable: false, rotateX: 600, rotateY: 1200 }
        interactivity:
            detect_on: canvas
            events:
                onhover: { enable: false, mode: grab }
                onclick: { enable: false, mode: push }
                resize: true
            modes:
                grab: { distance: 100, line_linked: { opacity: 0.5 } }
                bubble: { distance: 100, size: 40, duration: 0.4, opacity: 0.8, speed: 3 }
                repulse: { distance: 200, duration: 1.2 }
                push: { particles_nb: 100 }
                remove: { particles_nb: 2 }
        retina_detect: true
typed:
    type_speed: 0.7
    start_deplay: 0.7
    back_speed: 0.7
    back_delay: 0.7
    shuffle: false
    loop: false
    loop_count: false
    show_cursor: true
    cursor_char: '|'
    content_type: html
---

