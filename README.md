# JoOo Brand Launch Studio

An independent Claude plugin by Mostafa JoOo for creating product advertising campaigns with Higgsfield MCP. Version 1.1.1 (branding update). Not an official Higgsfield or Anthropic product.

## Install
In a Claude client that supports custom plugin marketplaces, add this repository URL through the plugin marketplace interface, then install jooo-brand-launch. If your client does not support repository import, use a ZIP of the skill folder with a compatible custom-skill importer and connect Higgsfield separately. Interface labels and feature availability depend on the client. Authorize the Higgsfield connector when prompted; no credentials are included. In a new chat invoke the jooo-brand-launch skill from the slash menu (the client may namespace it), attach a product reference and follow the approval gates.

The default campaign includes two 30-second cinematic commercials with shared voiceover, eight static ads, a 30-second UGC ad, a 30-second animated story and an interactive website. Arabic on-screen dialogue uses ElevenLabs with dialect and performance tags and MiniMax H3 audio/image references; English uses Seedance native dialogue by default. All models and costs must be verified at runtime. The user approves spending and publication. Simulation is text-only.

## Runtime integration
Discovers native workflows and permissions, plans against live balance, reconciles transactions when available, batches approved independent jobs, reuses supported Elements, and prefers native editing and licensed sound effects. All creative, financial and publication gates remain in force.

## Status
The previous 1.1.0 build was installed in Claude via ZIP. Installation of the renamed build, live generation and deployment remain untested. See the skill and references for detailed behavior.
