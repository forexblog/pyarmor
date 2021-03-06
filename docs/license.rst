.. _license:

License
=======

PyArmor is published as shareware. Free trial version never expires,
the limitations are

- The maximum size of code object is 35728 bytes in trial version
- The scripts obfuscated by trial version are not private. It means
  anyone could generate the license file which works for these
  obfuscated scripts.

About the license file of obfuscated scripts, refer to :ref:`The
License File for Obfuscated Script`

A registration code is required to obfuscate big code object or
generate private obfuscated scripts.

There are 2 basic types of licenses issued for the software. These are:

* A natural person usage license for home users. The user purchases one
  license to use the software on his own computer.

  Home users may use their natural person usage license on all computers
  and embedded devices which are property of the license owner.

* A juridical person usage license for business users. The user purchases
  one license to use the software for one product or one project of an
  organization.

  Business users may use their juridical person usage license on all
  computers and embedded devices for one product or project. But they
  require another license for different product or project.


Purchase
--------

To buy a license, please visit the following url

https://order.shareit.com/cart/add?vendorid=200089125&PRODUCT[300871197]=1

A registration code will be sent to your immediately after payment is
completed successfully.

After you receive the email which includes registration code, run the
following command to make it effective::

    pyarmor register CODE

Note that command `register` is introduced from `PyArmor` 5.3.3,
please upgrade the old version to the latest one, or directly replace
the content of `license.lic` in the `PyArmor` installed path with the
registration code only (no newline).
    
Check new license works by this command::

    pyarmor --version

The result should show ``PyArmor Version X.Y.Z`` and registration code.

After new license takes effect, you need obfuscate the scripts again,
and a random :ref:`Global Capsule` will be generated implicitly when
you run command ``pyarmor obfuscate``

**The registration code is valid forever, it can be used permanently.**

.. include:: _common_definitions.txt
