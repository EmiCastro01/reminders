## Reminders for Linux!

This project aims to provide a tool for saving and managing reminders on Linux. It allows users to create, view, and delete reminders through a simple command-line interface. 
This is my first Rust project, so I am still learning the language and its best practices. The code is not perfect, but it works! I plan to improve it over time and add more features as I learn.
For Contributors, i apologize in advance for the code quality, I am still learning Rust and I just wanted to get something working before worrying about code organization and best practices. I will refactor the code as I learn more about Rust and its ecosystem.

## TODO features:

- [ ] IMPORTANT!!: Modularize the code. I just put everything in one file for simplicity.
- [ ] Do the alerting system, which will notify the user when a reminder is due.
- [ ] Move the reminders to a .local/share/reminders directory by editing the `REMINDERS_FILE` variable in the code.
- [ ] Add a feature to edit existing reminders.
- [ ] Add a feature to delete existing reminders.
- [ ] Add filters to view reminders based on date, time, or keywords.

## Usage:

- Adding a reminder: `./target/debug/reminders add` opens a prompt to enter the reminder details.
- Viewing reminders: `./target/debug/reminders show` displays all the saved reminders.

## Building:

To build this project ensure you have Rust installed, and this repository cloned. Then run:

```bash
cargo build 
```
This will compile the project and create an executable in the `target/debug` directory. You can run the executable to manage your reminders.
The commands could be ran by that path or move the binary to some of your $PATH and just run `rem [action]`


## Contributing:

Contributions are welcome! If you have any ideas for new features or improvements, feel free to fork the repository and submit a pull request. Please ensure that your code is well-documented and follows the existing style of the project.

## License:
This project is licensed under the MIT License. See the LICENSE file for details.
