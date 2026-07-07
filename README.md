# XJall

class Human {
  constructor() {
    this.age = 0;
  }

  live() {
    this.age++;
    return this;
  }
}

class XJall extends Human {
  constructor() {
    super();
    this.curiosity = Infinity;
  }

  learn() {
    return this.live();
  }

  build() {
    return this.learn();
  }

  get legacy() {
    throw new Error("Implemented by the future.");
  }
}

export default new XJall();

Software developer from Indonesia.

Currently learning, building, and exploring new technologies.

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,javascript,nodejs,linux,docker,git" />
</p>

## GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=XJall&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=XJall&show_icons=true&theme=tokyonight" />
</p>

## Contributions

<p align="center">
  <img src="https://raw.githubusercontent.com/XJall/XJall/output/github-contribution-grid-snake.svg" />
</p>
