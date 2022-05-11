# layline.io Sample Project: Sample ASN.1 TAP3

Working example for

1. How to configire a ASN.1 format (based on TAP3.11)
2. How to read from a ASN.1 file
3. How to write to a ASN.1 file
4. How to output messages to the log

using layline.io.

## Description

* Using layline.io for message processing this example Project demonstrates the above.
* Use this to check how this is done and potentially use a similar setup in your Project.
* A sample file to read from is provided.
* All I/O operations are against files and local directory

## Getting Started

### Dependencies

* layline.io v0.9.3 or higher. Download [here](https://layline.io/download).
* supported OS (Windows, macOS, linux)

### Installing Project

#### On local installation

* Checkout to a directory of your choice
* Start _Layline Configuration Server_ and _Layline Configuration Center_ (web UI).
* Using the Configuration Center, import the project.
* Read [here](https://doc.layline.io/doc/wf-config/configuration.html#importing-a-project-directory) how to import a Project.


#### On layline.io docker image

* This Project comes pre-installed on the layline.io docker image.
* If you haven't used the layline.io docker image, make sure docker is installed as a prerequisite and then run `docker run -p 5841:5841 -p 5842:5842 docker.io/layline/layline-samples:1.0.0`.

Executing program

* There is a comprehensive blog about how to understand and run this particular Project which you can find [here](http://localhost:3000/blog/2022-02-14)

## Help

If you need help with this Project, please [contact us](mailto:support@layline.io). We **will** answer :-)

## Version History

* 0.1
  * Initial Release

## License

All files and content in this repository are released under the [MIT](https://opensource.org/licenses/MIT) license.
See the `license.txt` file  for details.

## More Resources

* [Blog explainer for this Project](http://localhost:3000/blog/2022-05-11)
* [layline.io Documentation](https://doc.layline.io)
* [Getting Started](https://doc.layline.io/quickstart/)
* [Importing a Project](https://doc.layline.io/doc/wf-config/configuration.html#importing-a-project-directory)
