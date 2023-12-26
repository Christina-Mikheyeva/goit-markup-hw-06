# goit-markup-hw-04

One of the ways to add SVG tru pseudo-elements.

.decoration::before {

    content: ''; display: block; height: 112px;
    border: 1px solid var(--light-slate); border-radius: 4px;

    background-color: var(--cloud-color);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 64px 64px;
}

.item:nth-child(1)::before { background-image:
url(/images/decorations/antenna.svg); }

.item:nth-child(2)::before { background-image:
url(/images/decorations/clock.svg); }

.item:nth-child(3)::before { background-image:
url(/images/decorations/diagram.svg); }

.item:nth-child(4)::before { background-image:
url(/images/decorations/astronaut.svg); } 



Button Subscribe

.subscribe::after { content: ""; width: 24px; height: 24px;

    background-image: url(../images/subscribe-plane-icon.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-color: transparent;
    background-size: 24px 24px;
} 
