# CBPatcher
A tool to patch a 32 bit iOS kernelcache for use in a jailbroken environment.

iOS 9.x and 10.x support initially, more OS's to come.

## How to use
    ./CBPatcher <in> <out> <version> [--nosb]

## Sample Usage
    ./CBPatcher kernelcache.n42 pwnkc.n42 9.3.5

## Option
    --nosb: Stop patching sandbox policies.
