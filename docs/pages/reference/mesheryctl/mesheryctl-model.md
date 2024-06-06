---
layout: default
title: mesheryctl-model
permalink: reference/mesheryctl/model
redirect_from: reference/mesheryctl/model/
type: reference
display-title: "false"
language: en
command: model
subcommand: nil
---

# mesheryctl model

View list of models and detail of models

## Synopsis

View list of models and detailed information of a specific model
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model [flags]

</div>
</pre> 

## Examples

To view list of components
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model list

</div>
</pre> 

To view a specific model
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model view [model-name]

</div>
</pre> 

## Options

<pre class='codeblock-pre'>
<div class='codeblock'>
  -h, --help   help for model

</div>
</pre>

## Options inherited from parent commands

<pre class='codeblock-pre'>
<div class='codeblock'>
      --config string   path to config file (default "~/.meshery/config.yaml")
  -v, --verbose         verbose output

</div>
</pre>

## See Also

Go back to [command reference index](/reference/mesheryctl/), if you want to add content manually to the CLI documentation, please refer to the [instruction](/project/contributing/contributing-cli#preserving-manually-added-documentation) for guidance.