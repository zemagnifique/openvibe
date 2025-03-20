# Openvibe

Welcome to Openvibe — a chaotic, open-source game dev experiment. Build a game with no communication, just pure vibes. Anyone from the vibe coding community can contribute. Let’s see what happens.

## Rules
1. **No Communication**: No chatting, commenting, or coordinating with others. Your code and commits are your voice.
2. **Don’t Delete the GitHub Link**: Keep the link to this repo intact in the project (e.g., in credits or a text file).
3. **One Open Pull Request Per Person**: Submit one PR with your contribution—big or small—and that’s it.
4. **Stick to the Engine**: Use [Three.js](https://threejs.org/) as the base. Don’t overhaul the core framework.
5. **Keep It Open**: All contributions must stay open-source under the MIT License.
6. **Merge Rule**: PRs are merged in the order they’re received, as long as they work (no crashes or broken builds). First come, first merged.

## How to Contribute
- Fork the repo.
- Add your piece—code, assets, whatever fits—using Three.js.
- Update the [Credits](#credits) section below with your name and social link (optional).
- Submit a pull request by TBD.
- Watch the chaos unfold.

## What’s the Goal?
There isn’t one. It’s an experiment. Playable game? Total mess? Either way, it’s ours.


## Features

* World
	* Three.js scene
	* Cannon.js physics
	* Variable timescale
	* Frame skipping
	* FXAA anti-aliasing
* Characters
	* Third-person camera
	* Raycast character controller with capsule collisions
	* General state system
	* Character AI
* Vehicles
	* Cars
	* Airplanes
	* Helicopters

All planned features can be found in the [GitHub Projects](https://github.com/swift502/Sketchbook/projects).

## Usage

You can define your own scenes in Blender, and then read them with Sketchbook. Sketchbook needs to run on a local server such as [http-server](https://www.npmjs.com/package/http-server) or [webpack-dev-server](https://github.com/webpack/webpack-dev-server) to be able to load external assets.

<!-- #### Script tag -->

1. Import:

```html
<script src="sketchbook.min.js"></script>
```

2. Load a glb scene defined in Blender:

```javascript
const world = new Sketchbook.World('scene.glb');
```

## Contributing

1. Get the LTS version of [Node.js](https://nodejs.org/en/) 16
2. [Fork this repository](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
3. Run `npm install`
4. Run `npm run dev`
5. Make changes and test them out at http://localhost:8080
6. Commit and [make a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)!


## Credits
Add your name and social link (e.g., Twitter, GitHub, personal site) here when you contribute. Format it like this:
- [Benammou] - [[@theBenammou](https://x.com/theBenammou)]
- [Jan Bláha] - [[swift502](https://github.com/swift502)]

Example:
- [VibeCoder] - [https://github.com/vibecoder]

## License
This project is licensed under the MIT License—see the [LICENSE](LICENSE) file for details.
