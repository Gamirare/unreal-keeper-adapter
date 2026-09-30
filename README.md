# Keeper Adapter for Unreal Engine

Native plugin that keeps an Unreal project and Keeper Engine Data Storage on the same values.
Documentation and account: https://keeperengine.com

## Download
Go to Releases and take the zip that matches your engine version:
KeeperAdapter-<version>-UE<engine>.zip, for example KeeperAdapter-1.0.2-UE5.5.zip.
Supported: UE 5.3 – 5.8.

## Install
1. Unzip into <Project>/Plugins/KeeperAdapter
2. Restart the editor, enable "Keeper Adapter" in Edit → Plugins
3. Project Settings → Plugins → Keeper Adapter: set API URL and an API key
   (issued per environment in Data Storage → API keys)

## Not on Unreal?
Everything under the adapter is plain HTTP. Any engine can use the REST API of each table.

## Reporting issues
Use Issues in this repo. Include engine version, adapter version and the editor log.
