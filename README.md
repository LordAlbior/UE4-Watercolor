# Watercolor UE4 Post-Processing Shader

For my first attempt of produce something on the Unreal Engine, I choose to do implement an awesome watercolor shader paper I found. 
Due to my limited knowledge of Unreal and some limitations of the engine, I only did an approximation of the paper technique.
I will continue to improve this shader as I progress on my studies of the engine. I'll put some pictures later.


## Installation

Copy the folder Materials on project root to your project or use my project as base to your own.

## Usage

There is a shader named M_BaseMaterial you can base your own shaders. Every object on the scene must have a material based on this shaders.
Also, four post-processing shaders must be added to your Post Processing volume in order:

* M_CelShader
* M_Wobbling
* M_Edge
* M_Paper

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

This project was based on the paper 
> Bousseau, Adrien, Matt Kaplan, Joëlle Thollot and François X. Sillion. “Interactive watercolor rendering with temporal coherence and abstraction.” NPAR (2006).


## License

This code is released under a MIT License.
