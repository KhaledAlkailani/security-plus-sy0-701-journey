# Stateful vs Stateless

## Stateless

Evaluates packets independently against rules.

It does not inherently remember that earlier packets belonged to the same connection.

## Stateful

Tracks connection state in a state table.

It can recognize return traffic as belonging to an established session.

## Troubleshooting example

Asymmetric routing can cause problems with stateful inspection when the firewall does not observe both sides of the expected flow.
