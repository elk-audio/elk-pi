---
name: Elk Audio OS Issue template
about: Guidelines for submitting Issues for the OS image
title: ''
labels: ''
assignees: ''

---

You can submit here _generic issues_ about the Elk OS system image for the Elk Pi.

If you only need help or you are not sure if your problem is actually a bug, it's better to ask on the [Elk Audio Forum](https://forum.elk.audio) first.

Please verify the following before submitting an issue:

# Scope
Is the Issue about the OS itself or it is specific to one core component? For example, if you experience problems with the audio host SUSHI, it's better to submit an issue on [SUSHI repository's Issues section](https://github.com/elk-audio/sushi/issues).

Good examples of issues that can be reported here are:
  * Linux image problems, e.g. SSH setup, filesystem organization, boot sequence
  * Drivers and kernel problems (excluding the audio driver)
  * Feature request, e.g. "please add the software X to the distro"

# Checklist

Please describe your setup in the most complete way, so that we can try to reproduce your problem.
Include the following in your report:

  * Raspberry Pi model
  * Relevant configuration files
  * Relevant logs (e.g. obtained with systemd's `journalctl` command or Kernel's `dmesg`)
  * Instructions to reproduce the problem in a deterministic manner
