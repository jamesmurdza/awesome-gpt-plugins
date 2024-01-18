# How to use Binaries in GPT

You can upload any executable to a GPT, and it will be able to run the executable with arguments and make use of the output. Some things to take into consideration:

- The binary must be compiled for x86 Linux.
- The binary will need to be made executable before GPT can run it (chmod 755). Normally GPT will remember to do this, but it doesn't hurt to remind it in the prompt.
- You don't need to tell GPT the filename ofthe binary, this will be automatically passed into the context.
