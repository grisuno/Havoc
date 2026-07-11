# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis. See more [here](https://github.com/grisuno/ReadMenator)

**Total Files Parsed:** 378 | **Total Symbols Extracted:** 4965 | **Total Imports:** 1643

## Structural Knowledge Map
> **Note:** The visual graph below has been intelligently pruned to the top 300 most relevant nodes to prevent rendering crashes. Full details of all 378 files are documented below.

```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray:5 5,color:#aaa;
    client_include_global_hpp["global.hpp (hpp)"]
    class client_include_global_hpp mod;
    client_include_global_hpp_RegisteredCommand["RegisteredCommand"]
    class client_include_global_hpp_RegisteredCommand cls;
    client_include_global_hpp --> client_include_global_hpp_RegisteredCommand
    client_include_global_hpp_RegisteredModule["RegisteredModule"]
    class client_include_global_hpp_RegisteredModule cls;
    client_include_global_hpp --> client_include_global_hpp_RegisteredModule
    client_include_global_hpp_ListenerItem["ListenerItem"]
    class client_include_global_hpp_ListenerItem cls;
    client_include_global_hpp --> client_include_global_hpp_ListenerItem
    client_include_global_hpp_Listener["Listener"]
    class client_include_global_hpp_Listener cls;
    client_include_global_hpp --> client_include_global_hpp_Listener
    client_include_global_hpp_HAVOC_GLOBAL_HPP["HAVOC_GLOBAL_HPP"]
    class client_include_global_hpp_HAVOC_GLOBAL_HPP fn;
    client_include_global_hpp --> client_include_global_hpp_HAVOC_GLOBAL_HPP
    teamserver_cmd_server_teamserver_go["teamserver.go (go)"]
    class teamserver_cmd_server_teamserver_go mod;
    teamserver_cmd_server_teamserver_go_NewTeamserver["NewTeamserver"]
    class teamserver_cmd_server_teamserver_go_NewTeamserver fn;
    teamserver_cmd_server_teamserver_go --> teamserver_cmd_server_teamserver_go_NewTeamserver
    teamserver_cmd_server_teamserver_go_SetServerFlags["SetServerFlags"]
    class teamserver_cmd_server_teamserver_go_SetServerFlags fn;
    teamserver_cmd_server_teamserver_go --> teamserver_cmd_server_teamserver_go_SetServerFlags
    teamserver_cmd_server_teamserver_go_Start["Start"]
    class teamserver_cmd_server_teamserver_go_Start fn;
    teamserver_cmd_server_teamserver_go --> teamserver_cmd_server_teamserver_go_Start
    teamserver_cmd_server_teamserver_go_handleRequest["handleRequest"]
    class teamserver_cmd_server_teamserver_go_handleRequest fn;
    teamserver_cmd_server_teamserver_go --> teamserver_cmd_server_teamserver_go_handleRequest
    teamserver_cmd_server_teamserver_go_SetProfile["SetProfile"]
    class teamserver_cmd_server_teamserver_go_SetProfile fn;
    teamserver_cmd_server_teamserver_go --> teamserver_cmd_server_teamserver_go_SetProfile
    client_include_UserInterface_Widgets_Store_hpp["Store.hpp (hpp)"]
    class client_include_UserInterface_Widgets_Store_hpp mod;
    client_include_UserInterface_Widgets_Store_hpp_Store["Store"]
    class client_include_UserInterface_Widgets_Store_hpp_Store cls;
    client_include_UserInterface_Widgets_Store_hpp --> client_include_UserInterface_Widgets_Store_hpp_Store
    client_include_UserInterface_Widgets_Store_hpp_HAVOC_STORE_HPP["HAVOC_STORE_HPP"]
    class client_include_UserInterface_Widgets_Store_hpp_HAVOC_STORE_HPP fn;
    client_include_UserInterface_Widgets_Store_hpp --> client_include_UserInterface_Widgets_Store_hpp_HAVOC_STORE_HPP
    payloads_Demon_include_Demon_h["Demon.h (h)"]
    class payloads_Demon_include_Demon_h mod;
    payloads_Demon_include_Demon_h__CONFIG["_CONFIG"]
    class payloads_Demon_include_Demon_h__CONFIG cls;
    payloads_Demon_include_Demon_h --> payloads_Demon_include_Demon_h__CONFIG
    payloads_Demon_include_Demon_h_DEMON_DEMON_H["DEMON_DEMON_H"]
    class payloads_Demon_include_Demon_h_DEMON_DEMON_H fn;
    payloads_Demon_include_Demon_h --> payloads_Demon_include_Demon_h_DEMON_DEMON_H
    teamserver_pkg_agent_demons_go["demons.go (go)"]
    class teamserver_pkg_agent_demons_go mod;
    teamserver_pkg_agent_demons_go_UploadMemFileInChunks["UploadMemFileInChunks"]
    class teamserver_pkg_agent_demons_go_UploadMemFileInChunks fn;
    teamserver_pkg_agent_demons_go --> teamserver_pkg_agent_demons_go_UploadMemFileInChunks
    teamserver_pkg_agent_demons_go_TeamserverTaskPrepare["TeamserverTaskPrepare"]
    class teamserver_pkg_agent_demons_go_TeamserverTaskPrepare fn;
    teamserver_pkg_agent_demons_go --> teamserver_pkg_agent_demons_go_TeamserverTaskPrepare
    teamserver_pkg_agent_demons_go_TaskPrepare["TaskPrepare"]
    class teamserver_pkg_agent_demons_go_TaskPrepare fn;
    teamserver_pkg_agent_demons_go --> teamserver_pkg_agent_demons_go_TaskPrepare
    teamserver_pkg_agent_demons_go_TaskDispatch["TaskDispatch"]
    class teamserver_pkg_agent_demons_go_TaskDispatch fn;
    teamserver_pkg_agent_demons_go --> teamserver_pkg_agent_demons_go_TaskDispatch
    teamserver_pkg_agent_demons_go_Console["Console"]
    class teamserver_pkg_agent_demons_go_Console fn;
    teamserver_pkg_agent_demons_go --> teamserver_pkg_agent_demons_go_Console
    teamserver_pkg_agent_agent_go["agent.go (go)"]
    class teamserver_pkg_agent_agent_go mod;
    teamserver_pkg_agent_agent_go_BuildPayloadMessage["BuildPayloadMessage"]
    class teamserver_pkg_agent_agent_go_BuildPayloadMessage fn;
    teamserver_pkg_agent_agent_go --> teamserver_pkg_agent_agent_go_BuildPayloadMessage
    teamserver_pkg_agent_agent_go_ParseHeader["ParseHeader"]
    class teamserver_pkg_agent_agent_go_ParseHeader fn;
    teamserver_pkg_agent_agent_go --> teamserver_pkg_agent_agent_go_ParseHeader
    teamserver_pkg_agent_agent_go_RegisterInfoToInstance["RegisterInfoToInstance"]
    class teamserver_pkg_agent_agent_go_RegisterInfoToInstance fn;
    teamserver_pkg_agent_agent_go --> teamserver_pkg_agent_agent_go_RegisterInfoToInstance
    teamserver_pkg_agent_agent_go_ParseDemonRegisterRequest["ParseDemonRegisterRequest"]
    class teamserver_pkg_agent_agent_go_ParseDemonRegisterRequest fn;
    teamserver_pkg_agent_agent_go --> teamserver_pkg_agent_agent_go_ParseDemonRegisterRequest
    teamserver_pkg_agent_agent_go_IsKnownRequestID["IsKnownRequestID"]
    class teamserver_pkg_agent_agent_go_IsKnownRequestID fn;
    teamserver_pkg_agent_agent_go --> teamserver_pkg_agent_agent_go_IsKnownRequestID
    client_src_UserInterface_Widgets_TeamserverTabSession_cc["TeamserverTabSession.cc (cc)"]
    class client_src_UserInterface_Widgets_TeamserverTabSession_cc mod;
    client_src_UserInterface_Widgets_TeamserverTabSession_cc_setupUi["setupUi"]
    class client_src_UserInterface_Widgets_TeamserverTabSession_cc_setupUi fn;
    client_src_UserInterface_Widgets_TeamserverTabSession_cc --> client_src_UserInterface_Widgets_TeamserverTabSession_cc_setupUi
    client_src_UserInterface_Widgets_TeamserverTabSession_cc_connect["connect"]
    class client_src_UserInterface_Widgets_TeamserverTabSession_cc_connect fn;
    client_src_UserInterface_Widgets_TeamserverTabSession_cc --> client_src_UserInterface_Widgets_TeamserverTabSession_cc_connect
    client_src_UserInterface_Widgets_TeamserverTabSession_cc_connect["connect"]
    class client_src_UserInterface_Widgets_TeamserverTabSession_cc_connect fn;
    client_src_UserInterface_Widgets_TeamserverTabSession_cc --> client_src_UserInterface_Widgets_TeamserverTabSession_cc_connect
    client_src_UserInterface_Widgets_TeamserverTabSession_cc_handleDemonContextMenu["handleDemonContextMenu"]
    class client_src_UserInterface_Widgets_TeamserverTabSession_cc_handleDemonContextMenu fn;
    client_src_UserInterface_Widgets_TeamserverTabSession_cc --> client_src_UserInterface_Widgets_TeamserverTabSession_cc_handleDemonContextMenu
    client_src_UserInterface_Widgets_TeamserverTabSession_cc_NewBottomTab["NewBottomTab"]
    class client_src_UserInterface_Widgets_TeamserverTabSession_cc_NewBottomTab fn;
    client_src_UserInterface_Widgets_TeamserverTabSession_cc --> client_src_UserInterface_Widgets_TeamserverTabSession_cc_NewBottomTab
    client_include_UserInterface_Dialogs_Listener_hpp["Listener.hpp (hpp)"]
    class client_include_UserInterface_Dialogs_Listener_hpp mod;
    client_include_UserInterface_Dialogs_Listener_hpp_HAVOC_LISTENER_HPP["HAVOC_LISTENER_HPP"]
    class client_include_UserInterface_Dialogs_Listener_hpp_HAVOC_LISTENER_HPP fn;
    client_include_UserInterface_Dialogs_Listener_hpp --> client_include_UserInterface_Dialogs_Listener_hpp_HAVOC_LISTENER_HPP
    client_src_UserInterface_Widgets_SessionGraph_cc["SessionGraph.cc (cc)"]
    class client_src_UserInterface_Widgets_SessionGraph_cc mod;
    client_src_UserInterface_Widgets_SessionGraph_cc_GraphWidget["GraphWidget"]
    class client_src_UserInterface_Widgets_SessionGraph_cc_GraphWidget fn;
    client_src_UserInterface_Widgets_SessionGraph_cc --> client_src_UserInterface_Widgets_SessionGraph_cc_GraphWidget
    client_src_UserInterface_Widgets_SessionGraph_cc_GraphNodeAdd["GraphNodeAdd"]
    class client_src_UserInterface_Widgets_SessionGraph_cc_GraphNodeAdd fn;
    client_src_UserInterface_Widgets_SessionGraph_cc --> client_src_UserInterface_Widgets_SessionGraph_cc_GraphNodeAdd
    client_src_UserInterface_Widgets_SessionGraph_cc_GraphNodeRemove["GraphNodeRemove"]
    class client_src_UserInterface_Widgets_SessionGraph_cc_GraphNodeRemove fn;
    client_src_UserInterface_Widgets_SessionGraph_cc --> client_src_UserInterface_Widgets_SessionGraph_cc_GraphNodeRemove
    client_src_UserInterface_Widgets_SessionGraph_cc_GraphPivotNodeAdd["GraphPivotNodeAdd"]
    class client_src_UserInterface_Widgets_SessionGraph_cc_GraphPivotNodeAdd fn;
    client_src_UserInterface_Widgets_SessionGraph_cc --> client_src_UserInterface_Widgets_SessionGraph_cc_GraphPivotNodeAdd
    client_src_UserInterface_Widgets_SessionGraph_cc_GraphPivotNodeDisconnect["GraphPivotNodeDisconnect"]
    class client_src_UserInterface_Widgets_SessionGraph_cc_GraphPivotNodeDisconnect fn;
    client_src_UserInterface_Widgets_SessionGraph_cc --> client_src_UserInterface_Widgets_SessionGraph_cc_GraphPivotNodeDisconnect
    client_src_UserInterface_HavocUi_cc["HavocUi.cc (cc)"]
    class client_src_UserInterface_HavocUi_cc mod;
    client_src_UserInterface_HavocUi_cc_setupUi["setupUi"]
    class client_src_UserInterface_HavocUi_cc_setupUi fn;
    client_src_UserInterface_HavocUi_cc --> client_src_UserInterface_HavocUi_cc_setupUi
    client_src_UserInterface_HavocUi_cc_OneSecondTick["OneSecondTick"]
    class client_src_UserInterface_HavocUi_cc_OneSecondTick fn;
    client_src_UserInterface_HavocUi_cc --> client_src_UserInterface_HavocUi_cc_OneSecondTick
    client_src_UserInterface_HavocUi_cc_MarkSessionAs["MarkSessionAs"]
    class client_src_UserInterface_HavocUi_cc_MarkSessionAs fn;
    client_src_UserInterface_HavocUi_cc --> client_src_UserInterface_HavocUi_cc_MarkSessionAs
    client_src_UserInterface_HavocUi_cc_UpdateSessionsHealth["UpdateSessionsHealth"]
    class client_src_UserInterface_HavocUi_cc_UpdateSessionsHealth fn;
    client_src_UserInterface_HavocUi_cc --> client_src_UserInterface_HavocUi_cc_UpdateSessionsHealth
    client_src_UserInterface_HavocUi_cc_retranslateUi["retranslateUi"]
    class client_src_UserInterface_HavocUi_cc_retranslateUi fn;
    client_src_UserInterface_HavocUi_cc --> client_src_UserInterface_HavocUi_cc_retranslateUi
    teamserver_pkg_common_builder_builder_go["builder.go (go)"]
    class teamserver_pkg_common_builder_builder_go mod;
    teamserver_pkg_common_builder_builder_go_NewBuilder["NewBuilder"]
    class teamserver_pkg_common_builder_builder_go_NewBuilder fn;
    teamserver_pkg_common_builder_builder_go --> teamserver_pkg_common_builder_builder_go_NewBuilder
    teamserver_pkg_common_builder_builder_go_SetSilent["SetSilent"]
    class teamserver_pkg_common_builder_builder_go_SetSilent fn;
    teamserver_pkg_common_builder_builder_go --> teamserver_pkg_common_builder_builder_go_SetSilent
    teamserver_pkg_common_builder_builder_go_Build["Build"]
    class teamserver_pkg_common_builder_builder_go_Build fn;
    teamserver_pkg_common_builder_builder_go --> teamserver_pkg_common_builder_builder_go_Build
    teamserver_pkg_common_builder_builder_go_SetListener["SetListener"]
    class teamserver_pkg_common_builder_builder_go_SetListener fn;
    teamserver_pkg_common_builder_builder_go --> teamserver_pkg_common_builder_builder_go_SetListener
    teamserver_pkg_common_builder_builder_go_SetPatchConfig["SetPatchConfig"]
    class teamserver_pkg_common_builder_builder_go_SetPatchConfig fn;
    teamserver_pkg_common_builder_builder_go --> teamserver_pkg_common_builder_builder_go_SetPatchConfig
    teamserver_pkg_common_util_go["util.go (go)"]
    class teamserver_pkg_common_util_go mod;
    teamserver_pkg_common_util_go_ParseWorkingHours["ParseWorkingHours"]
    class teamserver_pkg_common_util_go_ParseWorkingHours fn;
    teamserver_pkg_common_util_go --> teamserver_pkg_common_util_go_ParseWorkingHours
    teamserver_pkg_common_util_go_Bmp2Png["Bmp2Png"]
    class teamserver_pkg_common_util_go_Bmp2Png fn;
    teamserver_pkg_common_util_go --> teamserver_pkg_common_util_go_Bmp2Png
    teamserver_pkg_common_util_go_DecodeUTF16["DecodeUTF16"]
    class teamserver_pkg_common_util_go_DecodeUTF16 fn;
    teamserver_pkg_common_util_go --> teamserver_pkg_common_util_go_DecodeUTF16
    teamserver_pkg_common_util_go_EncodeUTF16["EncodeUTF16"]
    class teamserver_pkg_common_util_go_EncodeUTF16 fn;
    teamserver_pkg_common_util_go --> teamserver_pkg_common_util_go_EncodeUTF16
    teamserver_pkg_common_util_go_EncodeUTF8["EncodeUTF8"]
    class teamserver_pkg_common_util_go_EncodeUTF8 fn;
    teamserver_pkg_common_util_go --> teamserver_pkg_common_util_go_EncodeUTF8
    client_include_UserInterface_HavocUI_hpp["HavocUI.hpp (hpp)"]
    class client_include_UserInterface_HavocUI_hpp mod;
    client_include_UserInterface_HavocUI_hpp_HAVOC_HAVOCUI_HPP["HAVOC_HAVOCUI_HPP"]
    class client_include_UserInterface_HavocUI_hpp_HAVOC_HAVOCUI_HPP fn;
    client_include_UserInterface_HavocUI_hpp --> client_include_UserInterface_HavocUI_hpp_HAVOC_HAVOCUI_HPP
    client_src_Havoc_Packager_cc["Packager.cc (cc)"]
    class client_src_Havoc_Packager_cc mod;
    client_src_Havoc_Packager_cc_DecodePackage["DecodePackage"]
    class client_src_Havoc_Packager_cc_DecodePackage fn;
    client_src_Havoc_Packager_cc --> client_src_Havoc_Packager_cc_DecodePackage
    client_src_Havoc_Packager_cc_foreach["foreach"]
    class client_src_Havoc_Packager_cc_foreach fn;
    client_src_Havoc_Packager_cc --> client_src_Havoc_Packager_cc_foreach
    client_src_Havoc_Packager_cc_EncodePackage["EncodePackage"]
    class client_src_Havoc_Packager_cc_EncodePackage fn;
    client_src_Havoc_Packager_cc --> client_src_Havoc_Packager_cc_EncodePackage
    client_src_Havoc_Packager_cc_DispatchInitConnection["DispatchInitConnection"]
    class client_src_Havoc_Packager_cc_DispatchInitConnection fn;
    client_src_Havoc_Packager_cc --> client_src_Havoc_Packager_cc_DispatchInitConnection
    client_src_Havoc_Packager_cc_DispatchListener["DispatchListener"]
    class client_src_Havoc_Packager_cc_DispatchListener fn;
    client_src_Havoc_Packager_cc --> client_src_Havoc_Packager_cc_DispatchListener
    teamserver_pkg_service_service_go["service.go (go)"]
    class teamserver_pkg_service_service_go mod;
    teamserver_pkg_service_service_go_NewService["NewService"]
    class teamserver_pkg_service_service_go_NewService fn;
    teamserver_pkg_service_service_go --> teamserver_pkg_service_service_go_NewService
    teamserver_pkg_service_service_go_Start["Start"]
    class teamserver_pkg_service_service_go_Start fn;
    teamserver_pkg_service_service_go --> teamserver_pkg_service_service_go_Start
    teamserver_pkg_service_service_go_handleConnection["handleConnection"]
    class teamserver_pkg_service_service_go_handleConnection fn;
    teamserver_pkg_service_service_go --> teamserver_pkg_service_service_go_handleConnection
    teamserver_pkg_service_service_go_authenticate["authenticate"]
    class teamserver_pkg_service_service_go_authenticate fn;
    teamserver_pkg_service_service_go --> teamserver_pkg_service_service_go_authenticate
    teamserver_pkg_service_service_go_routine["routine"]
    class teamserver_pkg_service_service_go_routine fn;
    teamserver_pkg_service_service_go --> teamserver_pkg_service_service_go_routine
    teamserver_pkg_handlers_http_go["http.go (go)"]
    class teamserver_pkg_handlers_http_go mod;
    teamserver_pkg_handlers_http_go_NewConfigHttp["NewConfigHttp"]
    class teamserver_pkg_handlers_http_go_NewConfigHttp fn;
    teamserver_pkg_handlers_http_go --> teamserver_pkg_handlers_http_go_NewConfigHttp
    teamserver_pkg_handlers_http_go_generateCertFiles["generateCertFiles"]
    class teamserver_pkg_handlers_http_go_generateCertFiles fn;
    teamserver_pkg_handlers_http_go --> teamserver_pkg_handlers_http_go_generateCertFiles
    teamserver_pkg_handlers_http_go_fake404["fake404"]
    class teamserver_pkg_handlers_http_go_fake404 fn;
    teamserver_pkg_handlers_http_go --> teamserver_pkg_handlers_http_go_fake404
    teamserver_pkg_handlers_http_go_request["request"]
    class teamserver_pkg_handlers_http_go_request fn;
    teamserver_pkg_handlers_http_go --> teamserver_pkg_handlers_http_go_request
    teamserver_pkg_handlers_http_go_Start["Start"]
    class teamserver_pkg_handlers_http_go_Start fn;
    teamserver_pkg_handlers_http_go --> teamserver_pkg_handlers_http_go_Start
    client_include_UserInterface_Widgets_FileBrowser_hpp["FileBrowser.hpp (hpp)"]
    class client_include_UserInterface_Widgets_FileBrowser_hpp mod;
    client_include_UserInterface_Widgets_FileBrowser_hpp__FileDirData["_FileDirData"]
    class client_include_UserInterface_Widgets_FileBrowser_hpp__FileDirData cls;
    client_include_UserInterface_Widgets_FileBrowser_hpp --> client_include_UserInterface_Widgets_FileBrowser_hpp__FileDirData
    client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowserTableItem["FileBrowserTableItem"]
    class client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowserTableItem cls;
    client_include_UserInterface_Widgets_FileBrowser_hpp --> client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowserTableItem
    client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowserTreeItem["FileBrowserTreeItem"]
    class client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowserTreeItem cls;
    client_include_UserInterface_Widgets_FileBrowser_hpp --> client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowserTreeItem
    client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowser["FileBrowser"]
    class client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowser cls;
    client_include_UserInterface_Widgets_FileBrowser_hpp --> client_include_UserInterface_Widgets_FileBrowser_hpp_FileBrowser
    client_include_UserInterface_Widgets_FileBrowser_hpp_HAVOC_FILEBROWSER_HPP["HAVOC_FILEBROWSER_HPP"]
    class client_include_UserInterface_Widgets_FileBrowser_hpp_HAVOC_FILEBROWSER_HPP fn;
    client_include_UserInterface_Widgets_FileBrowser_hpp --> client_include_UserInterface_Widgets_FileBrowser_hpp_HAVOC_FILEBROWSER_HPP
    teamserver_pkg_common_certs_https_go["https.go (go)"]
    class teamserver_pkg_common_certs_https_go mod;
    teamserver_pkg_common_certs_https_go_randomState["randomState"]
    class teamserver_pkg_common_certs_https_go_randomState fn;
    teamserver_pkg_common_certs_https_go --> teamserver_pkg_common_certs_https_go_randomState
    teamserver_pkg_common_certs_https_go_randomLocality["randomLocality"]
    class teamserver_pkg_common_certs_https_go_randomLocality fn;
    teamserver_pkg_common_certs_https_go --> teamserver_pkg_common_certs_https_go_randomLocality
    teamserver_pkg_common_certs_https_go_randomStreetAddress["randomStreetAddress"]
    class teamserver_pkg_common_certs_https_go_randomStreetAddress fn;
    teamserver_pkg_common_certs_https_go --> teamserver_pkg_common_certs_https_go_randomStreetAddress
    teamserver_pkg_common_certs_https_go_randomProvinceLocalityStreetAddress["randomProvinceLocalityStreetAddress"]
    class teamserver_pkg_common_certs_https_go_randomProvinceLocalityStreetAddress fn;
    teamserver_pkg_common_certs_https_go --> teamserver_pkg_common_certs_https_go_randomProvinceLocalityStreetAddress
    teamserver_pkg_common_certs_https_go_randomPostalCode["randomPostalCode"]
    class teamserver_pkg_common_certs_https_go_randomPostalCode fn;
    teamserver_pkg_common_certs_https_go --> teamserver_pkg_common_certs_https_go_randomPostalCode
    client_src_Havoc_PythonApi_HavocUi_cc["HavocUi.cc (cc)"]
    class client_src_Havoc_PythonApi_HavocUi_cc mod;
    client_src_Havoc_PythonApi_HavocUi_cc_CreateTab["CreateTab"]
    class client_src_Havoc_PythonApi_HavocUi_cc_CreateTab fn;
    client_src_Havoc_PythonApi_HavocUi_cc --> client_src_Havoc_PythonApi_HavocUi_cc_CreateTab
    client_src_Havoc_PythonApi_HavocUi_cc_connect["connect"]
    class client_src_Havoc_PythonApi_HavocUi_cc_connect fn;
    client_src_Havoc_PythonApi_HavocUi_cc --> client_src_Havoc_PythonApi_HavocUi_cc_connect
    client_src_Havoc_PythonApi_HavocUi_cc_MessageBox["MessageBox"]
    class client_src_Havoc_PythonApi_HavocUi_cc_MessageBox fn;
    client_src_Havoc_PythonApi_HavocUi_cc --> client_src_Havoc_PythonApi_HavocUi_cc_MessageBox
    client_src_Havoc_PythonApi_HavocUi_cc_ErrorMessage["ErrorMessage"]
    class client_src_Havoc_PythonApi_HavocUi_cc_ErrorMessage fn;
    client_src_Havoc_PythonApi_HavocUi_cc --> client_src_Havoc_PythonApi_HavocUi_cc_ErrorMessage
    client_src_Havoc_PythonApi_HavocUi_cc_QuestionDialog["QuestionDialog"]
    class client_src_Havoc_PythonApi_HavocUi_cc_QuestionDialog fn;
    client_src_Havoc_PythonApi_HavocUi_cc --> client_src_Havoc_PythonApi_HavocUi_cc_QuestionDialog
    client_include_UserInterface_Dialogs_Payload_hpp["Payload.hpp (hpp)"]
    class client_include_UserInterface_Dialogs_Payload_hpp mod;
    client_include_UserInterface_Dialogs_Payload_hpp_Payload["Payload"]
    class client_include_UserInterface_Dialogs_Payload_hpp_Payload cls;
    client_include_UserInterface_Dialogs_Payload_hpp --> client_include_UserInterface_Dialogs_Payload_hpp_Payload
    client_include_UserInterface_Dialogs_Payload_hpp_HAVOC_STAGELESSDIALOG_H["HAVOC_STAGELESSDIALOG_H"]
    class client_include_UserInterface_Dialogs_Payload_hpp_HAVOC_STAGELESSDIALOG_H fn;
    client_include_UserInterface_Dialogs_Payload_hpp --> client_include_UserInterface_Dialogs_Payload_hpp_HAVOC_STAGELESSDIALOG_H
    client_include_UserInterface_Widgets_ProcessList_hpp["ProcessList.hpp (hpp)"]
    class client_include_UserInterface_Widgets_ProcessList_hpp mod;
    client_include_UserInterface_Widgets_ProcessList_hpp_HAVOC_PROCESSLIST_HPP["HAVOC_PROCESSLIST_HPP"]
    class client_include_UserInterface_Widgets_ProcessList_hpp_HAVOC_PROCESSLIST_HPP fn;
    client_include_UserInterface_Widgets_ProcessList_hpp --> client_include_UserInterface_Widgets_ProcessList_hpp_HAVOC_PROCESSLIST_HPP
    client_src_UserInterface_Widgets_LootWidget_cc["LootWidget.cc (cc)"]
    class client_src_UserInterface_Widgets_LootWidget_cc mod;
    client_src_UserInterface_Widgets_LootWidget_cc_ImageLabel["ImageLabel"]
    class client_src_UserInterface_Widgets_LootWidget_cc_ImageLabel fn;
    client_src_UserInterface_Widgets_LootWidget_cc --> client_src_UserInterface_Widgets_LootWidget_cc_ImageLabel
    client_src_UserInterface_Widgets_LootWidget_cc_resizeEvent["resizeEvent"]
    class client_src_UserInterface_Widgets_LootWidget_cc_resizeEvent fn;
    client_src_UserInterface_Widgets_LootWidget_cc --> client_src_UserInterface_Widgets_LootWidget_cc_resizeEvent
    client_src_UserInterface_Widgets_LootWidget_cc_pixmap["pixmap"]
    class client_src_UserInterface_Widgets_LootWidget_cc_pixmap fn;
    client_src_UserInterface_Widgets_LootWidget_cc --> client_src_UserInterface_Widgets_LootWidget_cc_pixmap
    client_src_UserInterface_Widgets_LootWidget_cc_event["event"]
    class client_src_UserInterface_Widgets_LootWidget_cc_event fn;
    client_src_UserInterface_Widgets_LootWidget_cc --> client_src_UserInterface_Widgets_LootWidget_cc_event
    client_src_UserInterface_Widgets_LootWidget_cc_keyReleaseEvent["keyReleaseEvent"]
    class client_src_UserInterface_Widgets_LootWidget_cc_keyReleaseEvent fn;
    client_src_UserInterface_Widgets_LootWidget_cc --> client_src_UserInterface_Widgets_LootWidget_cc_keyReleaseEvent
    teamserver_cmd_server_dispatch_go["dispatch.go (go)"]
    class teamserver_cmd_server_dispatch_go mod;
    teamserver_cmd_server_dispatch_go_DispatchEvent["DispatchEvent"]
    class teamserver_cmd_server_dispatch_go_DispatchEvent fn;
    teamserver_cmd_server_dispatch_go --> teamserver_cmd_server_dispatch_go_DispatchEvent
    payloads_Demon_src_core_Command_c["Command.c (c)"]
    class payloads_Demon_src_core_Command_c mod;
    payloads_Demon_src_core_Command_c_CommandDispatcher["CommandDispatcher"]
    class payloads_Demon_src_core_Command_c_CommandDispatcher fn;
    payloads_Demon_src_core_Command_c --> payloads_Demon_src_core_Command_c_CommandDispatcher
    payloads_Demon_src_core_Command_c_PRINTF["PRINTF"]
    class payloads_Demon_src_core_Command_c_PRINTF fn;
    payloads_Demon_src_core_Command_c --> payloads_Demon_src_core_Command_c_PRINTF
    payloads_Demon_src_core_Command_c_PUTS["PUTS"]
    class payloads_Demon_src_core_Command_c_PUTS fn;
    payloads_Demon_src_core_Command_c --> payloads_Demon_src_core_Command_c_PUTS
    payloads_Demon_src_core_Command_c_CommandSleep["CommandSleep"]
    class payloads_Demon_src_core_Command_c_CommandSleep fn;
    payloads_Demon_src_core_Command_c --> payloads_Demon_src_core_Command_c_CommandSleep
    payloads_Demon_src_core_Command_c_CommandJob["CommandJob"]
    class payloads_Demon_src_core_Command_c_CommandJob fn;
    payloads_Demon_src_core_Command_c --> payloads_Demon_src_core_Command_c_CommandJob
    teamserver_cmd_server_listener_go["listener.go (go)"]
    class teamserver_cmd_server_listener_go mod;
    teamserver_cmd_server_listener_go_ListenerStart["ListenerStart"]
    class teamserver_cmd_server_listener_go_ListenerStart fn;
    teamserver_cmd_server_listener_go --> teamserver_cmd_server_listener_go_ListenerStart
    teamserver_cmd_server_listener_go_ListenerExist["ListenerExist"]
    class teamserver_cmd_server_listener_go_ListenerExist fn;
    teamserver_cmd_server_listener_go --> teamserver_cmd_server_listener_go_ListenerExist
    teamserver_cmd_server_listener_go_ListenerGetInfo["ListenerGetInfo"]
    class teamserver_cmd_server_listener_go_ListenerGetInfo fn;
    teamserver_cmd_server_listener_go --> teamserver_cmd_server_listener_go_ListenerGetInfo
    teamserver_cmd_server_listener_go_ListenerRemove["ListenerRemove"]
    class teamserver_cmd_server_listener_go_ListenerRemove fn;
    teamserver_cmd_server_listener_go --> teamserver_cmd_server_listener_go_ListenerRemove
    teamserver_cmd_server_listener_go_ListenerEdit["ListenerEdit"]
    class teamserver_cmd_server_listener_go_ListenerEdit fn;
    teamserver_cmd_server_listener_go --> teamserver_cmd_server_listener_go_ListenerEdit
    client_include_Havoc_PythonApi_UI_PyDialogClass_hpp["PyDialogClass.hpp (hpp)"]
    class client_include_Havoc_PythonApi_UI_PyDialogClass_hpp mod;
    client_include_Havoc_PythonApi_UI_PyDialogClass_hpp_HAVOC_PYDIALOGCLASS_H["HAVOC_PYDIALOGCLASS_H"]
    class client_include_Havoc_PythonApi_UI_PyDialogClass_hpp_HAVOC_PYDIALOGCLASS_H fn;
    client_include_Havoc_PythonApi_UI_PyDialogClass_hpp --> client_include_Havoc_PythonApi_UI_PyDialogClass_hpp_HAVOC_PYDIALOGCLASS_H
    client_include_Havoc_PythonApi_UI_PyTreeClass_hpp["PyTreeClass.hpp (hpp)"]
    class client_include_Havoc_PythonApi_UI_PyTreeClass_hpp mod;
    client_include_Havoc_PythonApi_UI_PyTreeClass_hpp_HAVOC_PYTREECLASS_H["HAVOC_PYTREECLASS_H"]
    class client_include_Havoc_PythonApi_UI_PyTreeClass_hpp_HAVOC_PYTREECLASS_H fn;
    client_include_Havoc_PythonApi_UI_PyTreeClass_hpp --> client_include_Havoc_PythonApi_UI_PyTreeClass_hpp_HAVOC_PYTREECLASS_H
    client_include_Havoc_PythonApi_UI_PyWidgetClass_hpp["PyWidgetClass.hpp (hpp)"]
    class client_include_Havoc_PythonApi_UI_PyWidgetClass_hpp mod;
    client_include_Havoc_PythonApi_UI_PyWidgetClass_hpp_HAVOC_PYWIDGETCLASS_H["HAVOC_PYWIDGETCLASS_H"]
    class client_include_Havoc_PythonApi_UI_PyWidgetClass_hpp_HAVOC_PYWIDGETCLASS_H fn;
    client_include_Havoc_PythonApi_UI_PyWidgetClass_hpp --> client_include_Havoc_PythonApi_UI_PyWidgetClass_hpp_HAVOC_PYWIDGETCLASS_H
    client_include_Havoc_CmdLine_hpp["CmdLine.hpp (hpp)"]
    class client_include_Havoc_CmdLine_hpp mod;
    client_include_Havoc_CmdLine_hpp_is_same["is_same"]
    class client_include_Havoc_CmdLine_hpp_is_same cls;
    client_include_Havoc_CmdLine_hpp --> client_include_Havoc_CmdLine_hpp_is_same
    client_include_Havoc_CmdLine_hpp_default_reader["default_reader"]
    class client_include_Havoc_CmdLine_hpp_default_reader cls;
    client_include_Havoc_CmdLine_hpp --> client_include_Havoc_CmdLine_hpp_default_reader
    client_include_Havoc_CmdLine_hpp_range_reader["range_reader"]
    class client_include_Havoc_CmdLine_hpp_range_reader cls;
    client_include_Havoc_CmdLine_hpp --> client_include_Havoc_CmdLine_hpp_range_reader
    client_include_Havoc_CmdLine_hpp_oneof_reader["oneof_reader"]
    class client_include_Havoc_CmdLine_hpp_oneof_reader cls;
    client_include_Havoc_CmdLine_hpp --> client_include_Havoc_CmdLine_hpp_oneof_reader
    client_include_Havoc_CmdLine_hpp_lexical_cast_t["lexical_cast_t"]
    class client_include_Havoc_CmdLine_hpp_lexical_cast_t cls;
    client_include_Havoc_CmdLine_hpp --> client_include_Havoc_CmdLine_hpp_lexical_cast_t
    payloads_Demon_src_core_ObjectApi_c["ObjectApi.c (c)"]
    class payloads_Demon_src_core_ObjectApi_c mod;
    payloads_Demon_src_core_ObjectApi_c_LdrModulePebString["LdrModulePebString"]
    class payloads_Demon_src_core_ObjectApi_c_LdrModulePebString fn;
    payloads_Demon_src_core_ObjectApi_c --> payloads_Demon_src_core_ObjectApi_c_LdrModulePebString
    payloads_Demon_src_core_ObjectApi_c_LdrFunctionAddrString["LdrFunctionAddrString"]
    class payloads_Demon_src_core_ObjectApi_c_LdrFunctionAddrString fn;
    payloads_Demon_src_core_ObjectApi_c --> payloads_Demon_src_core_ObjectApi_c_LdrFunctionAddrString
    payloads_Demon_src_core_ObjectApi_c_LdrFreeLibrary["LdrFreeLibrary"]
    class payloads_Demon_src_core_ObjectApi_c_LdrFreeLibrary fn;
    payloads_Demon_src_core_ObjectApi_c --> payloads_Demon_src_core_ObjectApi_c_LdrFreeLibrary
    payloads_Demon_src_core_ObjectApi_c_LdrLocalFree["LdrLocalFree"]
    class payloads_Demon_src_core_ObjectApi_c_LdrLocalFree fn;
    payloads_Demon_src_core_ObjectApi_c --> payloads_Demon_src_core_ObjectApi_c_LdrLocalFree
    payloads_Demon_src_core_ObjectApi_c_swap_endianess["swap_endianess"]
    class payloads_Demon_src_core_ObjectApi_c_swap_endianess fn;
    payloads_Demon_src_core_ObjectApi_c --> payloads_Demon_src_core_ObjectApi_c_swap_endianess
    client_src_UserInterface_Widgets_ListenersTable_cc["ListenersTable.cc (cc)"]
    class client_src_UserInterface_Widgets_ListenersTable_cc mod;
    client_src_UserInterface_Widgets_ListenersTable_cc_setupUi["setupUi"]
    class client_src_UserInterface_Widgets_ListenersTable_cc_setupUi fn;
    client_src_UserInterface_Widgets_ListenersTable_cc --> client_src_UserInterface_Widgets_ListenersTable_cc_setupUi
    client_src_UserInterface_Widgets_ListenersTable_cc_ButtonsInit["ButtonsInit"]
    class client_src_UserInterface_Widgets_ListenersTable_cc_ButtonsInit fn;
    client_src_UserInterface_Widgets_ListenersTable_cc --> client_src_UserInterface_Widgets_ListenersTable_cc_ButtonsInit
    client_src_UserInterface_Widgets_ListenersTable_cc_connect["connect"]
    class client_src_UserInterface_Widgets_ListenersTable_cc_connect fn;
    client_src_UserInterface_Widgets_ListenersTable_cc --> client_src_UserInterface_Widgets_ListenersTable_cc_connect
    client_src_UserInterface_Widgets_ListenersTable_cc_connect["connect"]
    class client_src_UserInterface_Widgets_ListenersTable_cc_connect fn;
    client_src_UserInterface_Widgets_ListenersTable_cc --> client_src_UserInterface_Widgets_ListenersTable_cc_connect
    client_src_UserInterface_Widgets_ListenersTable_cc_connect["connect"]
    class client_src_UserInterface_Widgets_ListenersTable_cc_connect fn;
    client_src_UserInterface_Widgets_ListenersTable_cc --> client_src_UserInterface_Widgets_ListenersTable_cc_connect
    teamserver_pkg_utils_utils_go["utils.go (go)"]
    class teamserver_pkg_utils_utils_go mod;
    teamserver_pkg_utils_utils_go_UTF16BytesToString["UTF16BytesToString"]
    class teamserver_pkg_utils_utils_go_UTF16BytesToString fn;
    teamserver_pkg_utils_utils_go --> teamserver_pkg_utils_utils_go_UTF16BytesToString
    teamserver_pkg_utils_utils_go_GenerateID["GenerateID"]
    class teamserver_pkg_utils_utils_go_GenerateID fn;
    teamserver_pkg_utils_utils_go --> teamserver_pkg_utils_utils_go_GenerateID
    teamserver_pkg_utils_utils_go_GenerateString["GenerateString"]
    class teamserver_pkg_utils_utils_go_GenerateString fn;
    teamserver_pkg_utils_utils_go --> teamserver_pkg_utils_utils_go_GenerateString
    teamserver_pkg_utils_utils_go_EncodeCommand["EncodeCommand"]
    class teamserver_pkg_utils_utils_go_EncodeCommand fn;
    teamserver_pkg_utils_utils_go --> teamserver_pkg_utils_utils_go_EncodeCommand
    teamserver_pkg_utils_utils_go_IP2Inet["IP2Inet"]
    class teamserver_pkg_utils_utils_go_IP2Inet fn;
    teamserver_pkg_utils_utils_go --> teamserver_pkg_utils_utils_go_IP2Inet
    payloads_Demon_src_Demon_c["Demon.c (c)"]
    class payloads_Demon_src_Demon_c mod;
    payloads_Demon_src_Demon_c_DemonMain["DemonMain"]
    class payloads_Demon_src_Demon_c_DemonMain fn;
    payloads_Demon_src_Demon_c --> payloads_Demon_src_Demon_c_DemonMain
    payloads_Demon_src_Demon_c_DemonRoutine["DemonRoutine"]
    class payloads_Demon_src_Demon_c_DemonRoutine fn;
    payloads_Demon_src_Demon_c --> payloads_Demon_src_Demon_c_DemonRoutine
    payloads_Demon_src_Demon_c_DemonMetaData["DemonMetaData"]
    class payloads_Demon_src_Demon_c_DemonMetaData fn;
    payloads_Demon_src_Demon_c --> payloads_Demon_src_Demon_c_DemonMetaData
    payloads_Demon_src_Demon_c_DemonInit["DemonInit"]
    class payloads_Demon_src_Demon_c_DemonInit fn;
    payloads_Demon_src_Demon_c --> payloads_Demon_src_Demon_c_DemonInit
    payloads_Demon_src_Demon_c_PUTS["PUTS"]
    class payloads_Demon_src_Demon_c_PUTS fn;
    payloads_Demon_src_Demon_c --> payloads_Demon_src_Demon_c_PUTS
    client_src_UserInterface_Dialogs_Payload_cc["Payload.cc (cc)"]
    class client_src_UserInterface_Dialogs_Payload_cc mod;
    client_src_UserInterface_Dialogs_Payload_cc_setupUi["setupUi"]
    class client_src_UserInterface_Dialogs_Payload_cc_setupUi fn;
    client_src_UserInterface_Dialogs_Payload_cc --> client_src_UserInterface_Dialogs_Payload_cc_setupUi
    client_src_UserInterface_Dialogs_Payload_cc_connect["connect"]
    class client_src_UserInterface_Dialogs_Payload_cc_connect fn;
    client_src_UserInterface_Dialogs_Payload_cc --> client_src_UserInterface_Dialogs_Payload_cc_connect
    client_src_UserInterface_Dialogs_Payload_cc_buttonGenerate["buttonGenerate"]
    class client_src_UserInterface_Dialogs_Payload_cc_buttonGenerate fn;
    client_src_UserInterface_Dialogs_Payload_cc --> client_src_UserInterface_Dialogs_Payload_cc_buttonGenerate
    client_include_UserInterface_Widgets_Teamserver_hpp["Teamserver.hpp (hpp)"]
    class client_include_UserInterface_Widgets_Teamserver_hpp mod;
    client_include_UserInterface_Widgets_Teamserver_hpp_Teamserver["Teamserver"]
    class client_include_UserInterface_Widgets_Teamserver_hpp_Teamserver cls;
    client_include_UserInterface_Widgets_Teamserver_hpp --> client_include_UserInterface_Widgets_Teamserver_hpp_Teamserver
    client_include_UserInterface_Widgets_Teamserver_hpp_HAVOC_TEAMSERVER_HPP["HAVOC_TEAMSERVER_HPP"]
    class client_include_UserInterface_Widgets_Teamserver_hpp_HAVOC_TEAMSERVER_HPP fn;
    client_include_UserInterface_Widgets_Teamserver_hpp --> client_include_UserInterface_Widgets_Teamserver_hpp_HAVOC_TEAMSERVER_HPP
    client_src_Havoc_Demon_ConsoleInput_cc["ConsoleInput.cc (cc)"]
    class client_src_Havoc_Demon_ConsoleInput_cc mod;
    client_src_Havoc_Demon_ConsoleInput_cc_is_number["is_number"]
    class client_src_Havoc_Demon_ConsoleInput_cc_is_number fn;
    client_src_Havoc_Demon_ConsoleInput_cc --> client_src_Havoc_Demon_ConsoleInput_cc_is_number
    client_src_Havoc_Demon_ConsoleInput_cc_compareQString["compareQString"]
    class client_src_Havoc_Demon_ConsoleInput_cc_compareQString fn;
    client_src_Havoc_Demon_ConsoleInput_cc --> client_src_Havoc_Demon_ConsoleInput_cc_compareQString
    client_src_Havoc_Demon_ConsoleInput_cc_DemonCommands["DemonCommands"]
    class client_src_Havoc_Demon_ConsoleInput_cc_DemonCommands fn;
    client_src_Havoc_Demon_ConsoleInput_cc --> client_src_Havoc_Demon_ConsoleInput_cc_DemonCommands
    client_src_Havoc_Demon_ConsoleInput_cc_SEND["SEND"]
    class client_src_Havoc_Demon_ConsoleInput_cc_SEND fn;
    client_src_Havoc_Demon_ConsoleInput_cc --> client_src_Havoc_Demon_ConsoleInput_cc_SEND
    client_src_Havoc_Demon_ConsoleInput_cc_SEND["SEND"]
    class client_src_Havoc_Demon_ConsoleInput_cc_SEND fn;
    client_src_Havoc_Demon_ConsoleInput_cc --> client_src_Havoc_Demon_ConsoleInput_cc_SEND
    client_src_UserInterface_Widgets_DemonInteracted_cc["DemonInteracted.cc (cc)"]
    class client_src_UserInterface_Widgets_DemonInteracted_cc mod;
    client_src_UserInterface_Widgets_DemonInteracted_cc_DemonInput["DemonInput"]
    class client_src_UserInterface_Widgets_DemonInteracted_cc_DemonInput fn;
    client_src_UserInterface_Widgets_DemonInteracted_cc --> client_src_UserInterface_Widgets_DemonInteracted_cc_DemonInput
    client_src_UserInterface_Widgets_DemonInteracted_cc_handleKeyPress["handleKeyPress"]
    class client_src_UserInterface_Widgets_DemonInteracted_cc_handleKeyPress fn;
    client_src_UserInterface_Widgets_DemonInteracted_cc --> client_src_UserInterface_Widgets_DemonInteracted_cc_handleKeyPress
    client_src_UserInterface_Widgets_DemonInteracted_cc_handleTabKey["handleTabKey"]
    class client_src_UserInterface_Widgets_DemonInteracted_cc_handleTabKey fn;
    client_src_UserInterface_Widgets_DemonInteracted_cc --> client_src_UserInterface_Widgets_DemonInteracted_cc_handleTabKey
    client_src_UserInterface_Widgets_DemonInteracted_cc_handleUpKey["handleUpKey"]
    class client_src_UserInterface_Widgets_DemonInteracted_cc_handleUpKey fn;
    client_src_UserInterface_Widgets_DemonInteracted_cc --> client_src_UserInterface_Widgets_DemonInteracted_cc_handleUpKey
    client_src_UserInterface_Widgets_DemonInteracted_cc_handleDownKey["handleDownKey"]
    class client_src_UserInterface_Widgets_DemonInteracted_cc_handleDownKey fn;
    client_src_UserInterface_Widgets_DemonInteracted_cc --> client_src_UserInterface_Widgets_DemonInteracted_cc_handleDownKey
    payloads_Demon_include_core_Win32_h["Win32.h (h)"]
    class payloads_Demon_include_core_Win32_h mod;
    payloads_Demon_include_core_Win32_h__DIR_OR_FILE["_DIR_OR_FILE"]
    class payloads_Demon_include_core_Win32_h__DIR_OR_FILE cls;
    payloads_Demon_include_core_Win32_h --> payloads_Demon_include_core_Win32_h__DIR_OR_FILE
    payloads_Demon_include_core_Win32_h__SUB_DIR["_SUB_DIR"]
    class payloads_Demon_include_core_Win32_h__SUB_DIR cls;
    payloads_Demon_include_core_Win32_h --> payloads_Demon_include_core_Win32_h__SUB_DIR
    payloads_Demon_include_core_Win32_h__ROOT_DIR["_ROOT_DIR"]
    class payloads_Demon_include_core_Win32_h__ROOT_DIR cls;
    payloads_Demon_include_core_Win32_h --> payloads_Demon_include_core_Win32_h__ROOT_DIR
    payloads_Demon_include_core_Win32_h__BUFFER["_BUFFER"]
    class payloads_Demon_include_core_Win32_h__BUFFER cls;
    payloads_Demon_include_core_Win32_h --> payloads_Demon_include_core_Win32_h__BUFFER
    payloads_Demon_include_core_Win32_h__ANONPIPE["_ANONPIPE"]
    class payloads_Demon_include_core_Win32_h__ANONPIPE cls;
    payloads_Demon_include_core_Win32_h --> payloads_Demon_include_core_Win32_h__ANONPIPE
    client_src_UserInterface_Dialogs_Listener_cc["Listener.cc (cc)"]
    class client_src_UserInterface_Dialogs_Listener_cc mod;
    client_src_UserInterface_Dialogs_Listener_cc_is_number["is_number"]
    class client_src_UserInterface_Dialogs_Listener_cc_is_number fn;
    client_src_UserInterface_Dialogs_Listener_cc --> client_src_UserInterface_Dialogs_Listener_cc_is_number
    client_src_UserInterface_Dialogs_Listener_cc_NewListener["NewListener"]
    class client_src_UserInterface_Dialogs_Listener_cc_NewListener fn;
    client_src_UserInterface_Dialogs_Listener_cc --> client_src_UserInterface_Dialogs_Listener_cc_NewListener
    client_src_UserInterface_Dialogs_Listener_cc_connect["connect"]
    class client_src_UserInterface_Dialogs_Listener_cc_connect fn;
    client_src_UserInterface_Dialogs_Listener_cc --> client_src_UserInterface_Dialogs_Listener_cc_connect
    client_src_UserInterface_Dialogs_Listener_cc_connect["connect"]
    class client_src_UserInterface_Dialogs_Listener_cc_connect fn;
    client_src_UserInterface_Dialogs_Listener_cc --> client_src_UserInterface_Dialogs_Listener_cc_connect
    client_src_UserInterface_Dialogs_Listener_cc_connect["connect"]
    class client_src_UserInterface_Dialogs_Listener_cc_connect fn;
    client_src_UserInterface_Dialogs_Listener_cc --> client_src_UserInterface_Dialogs_Listener_cc_connect
    client_src_Havoc_PythonApi_Havoc_cc["Havoc.cc (cc)"]
    class client_src_Havoc_PythonApi_Havoc_cc mod;
    client_src_Havoc_PythonApi_Havoc_cc_PyInit_Havoc["PyInit_Havoc"]
    class client_src_Havoc_PythonApi_Havoc_cc_PyInit_Havoc fn;
    client_src_Havoc_PythonApi_Havoc_cc --> client_src_Havoc_PythonApi_Havoc_cc_PyInit_Havoc
    client_src_Havoc_PythonApi_Havoc_cc_Load["Load"]
    class client_src_Havoc_PythonApi_Havoc_cc_Load fn;
    client_src_Havoc_PythonApi_Havoc_cc --> client_src_Havoc_PythonApi_Havoc_cc_Load
    client_src_Havoc_PythonApi_Havoc_cc_GetListeners["GetListeners"]
    class client_src_Havoc_PythonApi_Havoc_cc_GetListeners fn;
    client_src_Havoc_PythonApi_Havoc_cc --> client_src_Havoc_PythonApi_Havoc_cc_GetListeners
    client_src_Havoc_PythonApi_Havoc_cc_GetAgents["GetAgents"]
    class client_src_Havoc_PythonApi_Havoc_cc_GetAgents fn;
    client_src_Havoc_PythonApi_Havoc_cc --> client_src_Havoc_PythonApi_Havoc_cc_GetAgents
    client_src_Havoc_PythonApi_Havoc_cc_GetDemons["GetDemons"]
    class client_src_Havoc_PythonApi_Havoc_cc_GetDemons fn;
    client_src_Havoc_PythonApi_Havoc_cc --> client_src_Havoc_PythonApi_Havoc_cc_GetDemons
    client_include_UserInterface_Widgets_LootWidget_h["LootWidget.h (h)"]
    class client_include_UserInterface_Widgets_LootWidget_h mod;
    client_include_UserInterface_Widgets_LootWidget_h_ImageLabel["ImageLabel"]
    class client_include_UserInterface_Widgets_LootWidget_h_ImageLabel cls;
    client_include_UserInterface_Widgets_LootWidget_h --> client_include_UserInterface_Widgets_LootWidget_h_ImageLabel
    client_include_UserInterface_Widgets_LootWidget_h_LootWidget["LootWidget"]
    class client_include_UserInterface_Widgets_LootWidget_h_LootWidget cls;
    client_include_UserInterface_Widgets_LootWidget_h --> client_include_UserInterface_Widgets_LootWidget_h_LootWidget
    client_include_UserInterface_Widgets_LootWidget_h_HAVOC_LOOTWIDGET_H["HAVOC_LOOTWIDGET_H"]
    class client_include_UserInterface_Widgets_LootWidget_h_HAVOC_LOOTWIDGET_H fn;
    client_include_UserInterface_Widgets_LootWidget_h --> client_include_UserInterface_Widgets_LootWidget_h_HAVOC_LOOTWIDGET_H
    teamserver_cmd_server_agent_go["agent.go (go)"]
    class teamserver_cmd_server_agent_go mod;
    teamserver_cmd_server_agent_go_AgentUpdate["AgentUpdate"]
    class teamserver_cmd_server_agent_go_AgentUpdate fn;
    teamserver_cmd_server_agent_go --> teamserver_cmd_server_agent_go_AgentUpdate
    teamserver_cmd_server_agent_go_Died["Died"]
    class teamserver_cmd_server_agent_go_Died fn;
    teamserver_cmd_server_agent_go --> teamserver_cmd_server_agent_go_Died
    teamserver_cmd_server_agent_go_UnlinkFromAll["UnlinkFromAll"]
    class teamserver_cmd_server_agent_go_UnlinkFromAll fn;
    teamserver_cmd_server_agent_go --> teamserver_cmd_server_agent_go_UnlinkFromAll
    teamserver_cmd_server_agent_go_ParentOf["ParentOf"]
    class teamserver_cmd_server_agent_go_ParentOf fn;
    teamserver_cmd_server_agent_go --> teamserver_cmd_server_agent_go_ParentOf
    teamserver_cmd_server_agent_go_LinksOf["LinksOf"]
    class teamserver_cmd_server_agent_go_LinksOf fn;
    teamserver_cmd_server_agent_go --> teamserver_cmd_server_agent_go_LinksOf
    payloads_Demon_src_inject_Inject_c["Inject.c (c)"]
    class payloads_Demon_src_inject_Inject_c mod;
    payloads_Demon_src_inject_Inject_c_Inject["Inject"]
    class payloads_Demon_src_inject_Inject_c_Inject fn;
    payloads_Demon_src_inject_Inject_c --> payloads_Demon_src_inject_Inject_c_Inject
    payloads_Demon_src_inject_Inject_c_PRINTF["PRINTF"]
    class payloads_Demon_src_inject_Inject_c_PRINTF fn;
    payloads_Demon_src_inject_Inject_c --> payloads_Demon_src_inject_Inject_c_PRINTF
    payloads_Demon_src_inject_Inject_c_PRINTF["PRINTF"]
    class payloads_Demon_src_inject_Inject_c_PRINTF fn;
    payloads_Demon_src_inject_Inject_c --> payloads_Demon_src_inject_Inject_c_PRINTF
    payloads_Demon_src_inject_Inject_c_PRINTF["PRINTF"]
    class payloads_Demon_src_inject_Inject_c_PRINTF fn;
    payloads_Demon_src_inject_Inject_c --> payloads_Demon_src_inject_Inject_c_PRINTF
    payloads_Demon_src_inject_Inject_c_PUTS["PUTS"]
    class payloads_Demon_src_inject_Inject_c_PUTS fn;
    payloads_Demon_src_inject_Inject_c --> payloads_Demon_src_inject_Inject_c_PUTS
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go["ast_body_test.go (go)"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go mod;
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodyGetAttribute["TestBodyGetAttribute"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodyGetAttribute fn;
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go --> teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodyGetAttribute
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodyFirstMatchingBlock["TestBodyFirstMatchingBlock"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodyFirstMatchingBlock fn;
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go --> teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodyFirstMatchingBlock
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeValue["TestBodySetAttributeValue"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeValue fn;
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go --> teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeValue
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeTraversal["TestBodySetAttributeTraversal"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeTraversal fn;
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go --> teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeTraversal
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeRaw["TestBodySetAttributeRaw"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeRaw fn;
    teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go --> teamserver_pkg_profile_yaotl_hclwrite_ast_body_test_go_TestBodySetAttributeRaw
    teamserver_cmd_server_types_go["types.go (go)"]
    class teamserver_cmd_server_types_go mod;
    teamserver_cmd_server_types_go_Listener["Listener"]
    class teamserver_cmd_server_types_go_Listener cls;
    teamserver_cmd_server_types_go --> teamserver_cmd_server_types_go_Listener
    teamserver_cmd_server_types_go_Client["Client"]
    class teamserver_cmd_server_types_go_Client cls;
    teamserver_cmd_server_types_go --> teamserver_cmd_server_types_go_Client
    teamserver_cmd_server_types_go_Users["Users"]
    class teamserver_cmd_server_types_go_Users cls;
    teamserver_cmd_server_types_go --> teamserver_cmd_server_types_go_Users
    teamserver_cmd_server_types_go_serverFlags["serverFlags"]
    class teamserver_cmd_server_types_go_serverFlags cls;
    teamserver_cmd_server_types_go --> teamserver_cmd_server_types_go_serverFlags
    teamserver_cmd_server_types_go_utilFlags["utilFlags"]
    class teamserver_cmd_server_types_go_utilFlags cls;
    teamserver_cmd_server_types_go --> teamserver_cmd_server_types_go_utilFlags
    client_src_UserInterface_Widgets_SessionTable_cc["SessionTable.cc (cc)"]
    class client_src_UserInterface_Widgets_SessionTable_cc mod;
    client_src_UserInterface_Widgets_SessionTable_cc_setupUi["setupUi"]
    class client_src_UserInterface_Widgets_SessionTable_cc_setupUi fn;
    client_src_UserInterface_Widgets_SessionTable_cc --> client_src_UserInterface_Widgets_SessionTable_cc_setupUi
    client_src_UserInterface_Widgets_SessionTable_cc_NewSessionItem["NewSessionItem"]
    class client_src_UserInterface_Widgets_SessionTable_cc_NewSessionItem fn;
    client_src_UserInterface_Widgets_SessionTable_cc --> client_src_UserInterface_Widgets_SessionTable_cc_NewSessionItem
    client_src_UserInterface_Widgets_SessionTable_cc_ChangeSessionValue["ChangeSessionValue"]
    class client_src_UserInterface_Widgets_SessionTable_cc_ChangeSessionValue fn;
    client_src_UserInterface_Widgets_SessionTable_cc --> client_src_UserInterface_Widgets_SessionTable_cc_ChangeSessionValue
    client_src_UserInterface_Widgets_SessionTable_cc_updateRow["updateRow"]
    class client_src_UserInterface_Widgets_SessionTable_cc_updateRow fn;
    client_src_UserInterface_Widgets_SessionTable_cc --> client_src_UserInterface_Widgets_SessionTable_cc_updateRow
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go["spec_test.go (go)"]
    class teamserver_pkg_profile_yaotl_specsuite_spec_test_go mod;
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go_TestMain["TestMain"]
    class teamserver_pkg_profile_yaotl_specsuite_spec_test_go_TestMain fn;
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go --> teamserver_pkg_profile_yaotl_specsuite_spec_test_go_TestMain
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go_build["build"]
    class teamserver_pkg_profile_yaotl_specsuite_spec_test_go_build fn;
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go --> teamserver_pkg_profile_yaotl_specsuite_spec_test_go_build
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go_TestSpec["TestSpec"]
    class teamserver_pkg_profile_yaotl_specsuite_spec_test_go_TestSpec fn;
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go --> teamserver_pkg_profile_yaotl_specsuite_spec_test_go_TestSpec
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go_goBuild["goBuild"]
    class teamserver_pkg_profile_yaotl_specsuite_spec_test_go_goBuild fn;
    teamserver_pkg_profile_yaotl_specsuite_spec_test_go --> teamserver_pkg_profile_yaotl_specsuite_spec_test_go_goBuild
    teamserver_cmd_server_go["server.go (go)"]
    class teamserver_cmd_server_go mod;
    teamserver_pkg_profile_yaotl_hcldec_spec_go["spec.go (go)"]
    class teamserver_pkg_profile_yaotl_hcldec_spec_go mod;
    teamserver_pkg_profile_yaotl_hcldec_spec_go_visitSameBodyChildren["visitSameBodyChildren"]
    class teamserver_pkg_profile_yaotl_hcldec_spec_go_visitSameBodyChildren fn;
    teamserver_pkg_profile_yaotl_hcldec_spec_go --> teamserver_pkg_profile_yaotl_hcldec_spec_go_visitSameBodyChildren
    teamserver_pkg_profile_yaotl_hcldec_spec_go_decode["decode"]
    class teamserver_pkg_profile_yaotl_hcldec_spec_go_decode fn;
    teamserver_pkg_profile_yaotl_hcldec_spec_go --> teamserver_pkg_profile_yaotl_hcldec_spec_go_decode
    teamserver_pkg_profile_yaotl_hcldec_spec_go_impliedType["impliedType"]
    class teamserver_pkg_profile_yaotl_hcldec_spec_go_impliedType fn;
    teamserver_pkg_profile_yaotl_hcldec_spec_go --> teamserver_pkg_profile_yaotl_hcldec_spec_go_impliedType
    teamserver_pkg_profile_yaotl_hcldec_spec_go_sourceRange["sourceRange"]
    class teamserver_pkg_profile_yaotl_hcldec_spec_go_sourceRange fn;
    teamserver_pkg_profile_yaotl_hcldec_spec_go --> teamserver_pkg_profile_yaotl_hcldec_spec_go_sourceRange
    teamserver_pkg_profile_yaotl_hcldec_spec_go_visitSameBodyChildren["visitSameBodyChildren"]
    class teamserver_pkg_profile_yaotl_hcldec_spec_go_visitSameBodyChildren fn;
    teamserver_pkg_profile_yaotl_hcldec_spec_go --> teamserver_pkg_profile_yaotl_hcldec_spec_go_visitSameBodyChildren
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go["parser.go (go)"]
    class teamserver_pkg_profile_yaotl_hclsyntax_parser_go mod;
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go_ParseBody["ParseBody"]
    class teamserver_pkg_profile_yaotl_hclsyntax_parser_go_ParseBody fn;
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go --> teamserver_pkg_profile_yaotl_hclsyntax_parser_go_ParseBody
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go_ParseBodyItem["ParseBodyItem"]
    class teamserver_pkg_profile_yaotl_hclsyntax_parser_go_ParseBodyItem fn;
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go --> teamserver_pkg_profile_yaotl_hclsyntax_parser_go_ParseBodyItem
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go_parseSingleAttrBody["parseSingleAttrBody"]
    class teamserver_pkg_profile_yaotl_hclsyntax_parser_go_parseSingleAttrBody fn;
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go --> teamserver_pkg_profile_yaotl_hclsyntax_parser_go_parseSingleAttrBody
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go_finishParsingBodyAttribute["finishParsingBodyAttribute"]
    class teamserver_pkg_profile_yaotl_hclsyntax_parser_go_finishParsingBodyAttribute fn;
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go --> teamserver_pkg_profile_yaotl_hclsyntax_parser_go_finishParsingBodyAttribute
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go_finishParsingBodyBlock["finishParsingBodyBlock"]
    class teamserver_pkg_profile_yaotl_hclsyntax_parser_go_finishParsingBodyBlock fn;
    teamserver_pkg_profile_yaotl_hclsyntax_parser_go --> teamserver_pkg_profile_yaotl_hclsyntax_parser_go_finishParsingBodyBlock
    payloads_Demon_src_core_CoffeeLdr_c["CoffeeLdr.c (c)"]
    class payloads_Demon_src_core_CoffeeLdr_c mod;
    payloads_Demon_src_core_CoffeeLdr_c_VehDebugger["VehDebugger"]
    class payloads_Demon_src_core_CoffeeLdr_c_VehDebugger fn;
    payloads_Demon_src_core_CoffeeLdr_c --> payloads_Demon_src_core_CoffeeLdr_c_VehDebugger
    payloads_Demon_src_core_CoffeeLdr_c_SymbolIncludesLibrary["SymbolIncludesLibrary"]
    class payloads_Demon_src_core_CoffeeLdr_c_SymbolIncludesLibrary fn;
    payloads_Demon_src_core_CoffeeLdr_c --> payloads_Demon_src_core_CoffeeLdr_c_SymbolIncludesLibrary
    payloads_Demon_src_core_CoffeeLdr_c_SymbolIsImport["SymbolIsImport"]
    class payloads_Demon_src_core_CoffeeLdr_c_SymbolIsImport fn;
    payloads_Demon_src_core_CoffeeLdr_c --> payloads_Demon_src_core_CoffeeLdr_c_SymbolIsImport
    payloads_Demon_src_core_CoffeeLdr_c_CoffeeProcessSymbol["CoffeeProcessSymbol"]
    class payloads_Demon_src_core_CoffeeLdr_c_CoffeeProcessSymbol fn;
    payloads_Demon_src_core_CoffeeLdr_c --> payloads_Demon_src_core_CoffeeLdr_c_CoffeeProcessSymbol
    payloads_Demon_src_core_CoffeeLdr_c_CoffeeFunction["CoffeeFunction"]
    class payloads_Demon_src_core_CoffeeLdr_c_CoffeeFunction fn;
    payloads_Demon_src_core_CoffeeLdr_c --> payloads_Demon_src_core_CoffeeLdr_c_CoffeeFunction
    teamserver_pkg_logger_logger_go["logger.go (go)"]
    class teamserver_pkg_logger_logger_go mod;
    teamserver_pkg_logger_logger_go_FunctionTrace["FunctionTrace"]
    class teamserver_pkg_logger_logger_go_FunctionTrace fn;
    teamserver_pkg_logger_logger_go --> teamserver_pkg_logger_logger_go_FunctionTrace
    teamserver_pkg_logger_logger_go_Info["Info"]
    class teamserver_pkg_logger_logger_go_Info fn;
    teamserver_pkg_logger_logger_go --> teamserver_pkg_logger_logger_go_Info
    teamserver_pkg_logger_logger_go_Good["Good"]
    class teamserver_pkg_logger_logger_go_Good fn;
    teamserver_pkg_logger_logger_go --> teamserver_pkg_logger_logger_go_Good
    teamserver_pkg_logger_logger_go_Debug["Debug"]
    class teamserver_pkg_logger_logger_go_Debug fn;
    teamserver_pkg_logger_logger_go --> teamserver_pkg_logger_logger_go_Debug
    teamserver_pkg_logger_logger_go_DebugError["DebugError"]
    class teamserver_pkg_logger_logger_go_DebugError fn;
    teamserver_pkg_logger_logger_go --> teamserver_pkg_logger_logger_go_DebugError
    teamserver_pkg_profile_yaotl_json_structure_test_go["structure_test.go (go)"]
    class teamserver_pkg_profile_yaotl_json_structure_test_go mod;
    teamserver_pkg_profile_yaotl_json_structure_test_go_TestBodyPartialContent["TestBodyPartialContent"]
    class teamserver_pkg_profile_yaotl_json_structure_test_go_TestBodyPartialContent fn;
    teamserver_pkg_profile_yaotl_json_structure_test_go --> teamserver_pkg_profile_yaotl_json_structure_test_go_TestBodyPartialContent
    teamserver_pkg_profile_yaotl_json_structure_test_go_TestBodyContent["TestBodyContent"]
    class teamserver_pkg_profile_yaotl_json_structure_test_go_TestBodyContent fn;
    teamserver_pkg_profile_yaotl_json_structure_test_go --> teamserver_pkg_profile_yaotl_json_structure_test_go_TestBodyContent
    teamserver_pkg_profile_yaotl_json_structure_test_go_TestJustAttributes["TestJustAttributes"]
    class teamserver_pkg_profile_yaotl_json_structure_test_go_TestJustAttributes fn;
    teamserver_pkg_profile_yaotl_json_structure_test_go --> teamserver_pkg_profile_yaotl_json_structure_test_go_TestJustAttributes
    teamserver_pkg_profile_yaotl_json_structure_test_go_TestExpressionVariables["TestExpressionVariables"]
    class teamserver_pkg_profile_yaotl_json_structure_test_go_TestExpressionVariables fn;
    teamserver_pkg_profile_yaotl_json_structure_test_go --> teamserver_pkg_profile_yaotl_json_structure_test_go_TestExpressionVariables
    teamserver_pkg_profile_yaotl_json_structure_test_go_TestExpressionAsTraversal["TestExpressionAsTraversal"]
    class teamserver_pkg_profile_yaotl_json_structure_test_go_TestExpressionAsTraversal fn;
    teamserver_pkg_profile_yaotl_json_structure_test_go --> teamserver_pkg_profile_yaotl_json_structure_test_go_TestExpressionAsTraversal
    teamserver_pkg_profile_yaotl_diagnostic_text_go["diagnostic_text.go (go)"]
    class teamserver_pkg_profile_yaotl_diagnostic_text_go mod;
    teamserver_pkg_profile_yaotl_diagnostic_text_go_NewDiagnosticTextWriter["NewDiagnosticTextWriter"]
    class teamserver_pkg_profile_yaotl_diagnostic_text_go_NewDiagnosticTextWriter fn;
    teamserver_pkg_profile_yaotl_diagnostic_text_go --> teamserver_pkg_profile_yaotl_diagnostic_text_go_NewDiagnosticTextWriter
    teamserver_pkg_profile_yaotl_diagnostic_text_go_WriteDiagnostic["WriteDiagnostic"]
    class teamserver_pkg_profile_yaotl_diagnostic_text_go_WriteDiagnostic fn;
    teamserver_pkg_profile_yaotl_diagnostic_text_go --> teamserver_pkg_profile_yaotl_diagnostic_text_go_WriteDiagnostic
    teamserver_pkg_profile_yaotl_diagnostic_text_go_WriteDiagnostics["WriteDiagnostics"]
    class teamserver_pkg_profile_yaotl_diagnostic_text_go_WriteDiagnostics fn;
    teamserver_pkg_profile_yaotl_diagnostic_text_go --> teamserver_pkg_profile_yaotl_diagnostic_text_go_WriteDiagnostics
    teamserver_pkg_profile_yaotl_diagnostic_text_go_traversalStr["traversalStr"]
    class teamserver_pkg_profile_yaotl_diagnostic_text_go_traversalStr fn;
    teamserver_pkg_profile_yaotl_diagnostic_text_go --> teamserver_pkg_profile_yaotl_diagnostic_text_go_traversalStr
    teamserver_pkg_profile_yaotl_diagnostic_text_go_valueStr["valueStr"]
    class teamserver_pkg_profile_yaotl_diagnostic_text_go_valueStr fn;
    teamserver_pkg_profile_yaotl_diagnostic_text_go --> teamserver_pkg_profile_yaotl_diagnostic_text_go_valueStr
    teamserver_pkg_logr_demon_go["demon.go (go)"]
    class teamserver_pkg_logr_demon_go mod;
    teamserver_pkg_logr_demon_go_AddAgentInput["AddAgentInput"]
    class teamserver_pkg_logr_demon_go_AddAgentInput fn;
    teamserver_pkg_logr_demon_go --> teamserver_pkg_logr_demon_go_AddAgentInput
    teamserver_pkg_logr_demon_go_AddAgentRaw["AddAgentRaw"]
    class teamserver_pkg_logr_demon_go_AddAgentRaw fn;
    teamserver_pkg_logr_demon_go --> teamserver_pkg_logr_demon_go_AddAgentRaw
    teamserver_pkg_logr_demon_go_DemonAddOutput["DemonAddOutput"]
    class teamserver_pkg_logr_demon_go_DemonAddOutput fn;
    teamserver_pkg_logr_demon_go --> teamserver_pkg_logr_demon_go_DemonAddOutput
    teamserver_pkg_logr_demon_go_DemonAddDownloadedFile["DemonAddDownloadedFile"]
    class teamserver_pkg_logr_demon_go_DemonAddDownloadedFile fn;
    teamserver_pkg_logr_demon_go --> teamserver_pkg_logr_demon_go_DemonAddDownloadedFile
    teamserver_pkg_logr_demon_go_DemonSaveScreenshot["DemonSaveScreenshot"]
    class teamserver_pkg_logr_demon_go_DemonSaveScreenshot fn;
    teamserver_pkg_logr_demon_go --> teamserver_pkg_logr_demon_go_DemonSaveScreenshot
    client_src_UserInterface_Widgets_Chat_cc["Chat.cc (cc)"]
    class client_src_UserInterface_Widgets_Chat_cc mod;
    client_src_UserInterface_Widgets_Chat_cc_setupUi["setupUi"]
    class client_src_UserInterface_Widgets_Chat_cc_setupUi fn;
    client_src_UserInterface_Widgets_Chat_cc --> client_src_UserInterface_Widgets_Chat_cc_setupUi
    client_src_UserInterface_Widgets_Chat_cc_AppendText["AppendText"]
    class client_src_UserInterface_Widgets_Chat_cc_AppendText fn;
    client_src_UserInterface_Widgets_Chat_cc --> client_src_UserInterface_Widgets_Chat_cc_AppendText
    client_src_UserInterface_Widgets_Chat_cc_AddUserMessage["AddUserMessage"]
    class client_src_UserInterface_Widgets_Chat_cc_AddUserMessage fn;
    client_src_UserInterface_Widgets_Chat_cc --> client_src_UserInterface_Widgets_Chat_cc_AddUserMessage
    client_src_UserInterface_Widgets_Chat_cc_AppendFromInput["AppendFromInput"]
    class client_src_UserInterface_Widgets_Chat_cc_AppendFromInput fn;
    client_src_UserInterface_Widgets_Chat_cc --> client_src_UserInterface_Widgets_Chat_cc_AppendFromInput
    payloads_Demon_src_core_Obf_c["Obf.c (c)"]
    class payloads_Demon_src_core_Obf_c mod;
    payloads_Demon_src_core_Obf_c_FoliageObf["FoliageObf"]
    class payloads_Demon_src_core_Obf_c_FoliageObf fn;
    payloads_Demon_src_core_Obf_c --> payloads_Demon_src_core_Obf_c_FoliageObf
    payloads_Demon_src_core_Obf_c_PRINTF["PRINTF"]
    class payloads_Demon_src_core_Obf_c_PRINTF fn;
    payloads_Demon_src_core_Obf_c --> payloads_Demon_src_core_Obf_c_PRINTF
    payloads_Demon_src_core_Obf_c_SleepTime["SleepTime"]
    class payloads_Demon_src_core_Obf_c_SleepTime fn;
    payloads_Demon_src_core_Obf_c --> payloads_Demon_src_core_Obf_c_SleepTime
    payloads_Demon_src_core_Obf_c_SleepObf["SleepObf"]
    class payloads_Demon_src_core_Obf_c_SleepObf fn;
    payloads_Demon_src_core_Obf_c --> payloads_Demon_src_core_Obf_c_SleepObf
    teamserver_pkg_events_demons_go["demons.go (go)"]
    class teamserver_pkg_events_demons_go mod;
    teamserver_pkg_events_demons_go_NewDemon["NewDemon"]
    class teamserver_pkg_events_demons_go_NewDemon fn;
    teamserver_pkg_events_demons_go --> teamserver_pkg_events_demons_go_NewDemon
    teamserver_pkg_events_demons_go_DemonOutput["DemonOutput"]
    class teamserver_pkg_events_demons_go_DemonOutput fn;
    teamserver_pkg_events_demons_go --> teamserver_pkg_events_demons_go_DemonOutput
    teamserver_pkg_events_demons_go_CallBack["CallBack"]
    class teamserver_pkg_events_demons_go_CallBack fn;
    teamserver_pkg_events_demons_go --> teamserver_pkg_events_demons_go_CallBack
    teamserver_pkg_events_demons_go_MarkAs["MarkAs"]
    class teamserver_pkg_events_demons_go_MarkAs fn;
    teamserver_pkg_events_demons_go --> teamserver_pkg_events_demons_go_MarkAs
    teamserver_pkg_handlers_handlers_go["handlers.go (go)"]
    class teamserver_pkg_handlers_handlers_go mod;
    teamserver_pkg_handlers_handlers_go_parseAgentRequest["parseAgentRequest"]
    class teamserver_pkg_handlers_handlers_go_parseAgentRequest fn;
    teamserver_pkg_handlers_handlers_go --> teamserver_pkg_handlers_handlers_go_parseAgentRequest
    teamserver_pkg_handlers_handlers_go_handleDemonAgent["handleDemonAgent"]
    class teamserver_pkg_handlers_handlers_go_handleDemonAgent fn;
    teamserver_pkg_handlers_handlers_go --> teamserver_pkg_handlers_handlers_go_handleDemonAgent
    teamserver_pkg_handlers_handlers_go_handleServiceAgent["handleServiceAgent"]
    class teamserver_pkg_handlers_handlers_go_handleServiceAgent fn;
    teamserver_pkg_handlers_handlers_go --> teamserver_pkg_handlers_handlers_go_handleServiceAgent
    teamserver_pkg_handlers_handlers_go_notifyTaskSize["notifyTaskSize"]
    class teamserver_pkg_handlers_handlers_go_notifyTaskSize fn;
    teamserver_pkg_handlers_handlers_go --> teamserver_pkg_handlers_handlers_go_notifyTaskSize
    teamserver_pkg_profile_yaotl_hclwrite_ast_block_test_go["ast_block_test.go (go)"]
    class teamserver_pkg_profile_yaotl_hclwrite_ast_block_test_go mod;
```

---

## Architecture Reference

### ASM (4 files)

#### `Spoof.x64.asm`
**Path:** `payloads/Demon/src/asm/Spoof.x64.asm`

**Functions:**
- `Spoof` (line 8)
- `fixup` (line 22)

#### `Spoof.x86.asm`
**Path:** `payloads/Demon/src/asm/Spoof.x86.asm`

**Functions:**
- `_Spoof` (line 8)

#### `Syscall.x64.asm`
**Path:** `payloads/Demon/src/asm/Syscall.x64.asm`

*No symbols extracted*

#### `Syscall.x86.asm`
**Path:** `payloads/Demon/src/asm/Syscall.x86.asm`

*No symbols extracted*

### C (38 files)

#### `Demon.c`
**Path:** `payloads/Demon/src/Demon.c`

**Functions:**
- `DemonMain` (line 34) `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )` - *In DemonMain it should go as followed:  1. Initialize pointer, modules and win32 api 2. Initialize metadata 3. Parse config 4. Enter main connectin...*
- `DemonRoutine` (line 63) `_Noreturn
VOID DemonRoutine()` - *Main demon routine:  1. Connect to listener 2. Go into tasking routine: A. Sleep Obfuscation. B. Request for the task queue C. Parse Task D. Execut...*
- `DemonMetaData` (line 95) `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )` - *} if ( Instance->Session.Connected ) { /* Enter tasking routine CommandDispatcher(); } /* Sleep for a while (with encryption if specified) SleepObf...*
- `DemonInit` (line 266) `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )`
- `PUTS` (line 290) `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...` - *ifdef TRANSPORT_HTTP*
- `PRINTF` (line 569) `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()`
- `PRINTF` (line 645) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- `PRINTF` (line 672) `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...`
- `PRINTF` (line 775) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`

#### `CoffeeLdr.c`
**Path:** `payloads/Demon/src/core/CoffeeLdr.c`

**Functions:**
- `VehDebugger` (line 31) `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )`
- `SymbolIncludesLibrary` (line 64) `BOOL SymbolIncludesLibrary( LPSTR Symbol )` - *check if the symbol is on the form: __imp_LIBNAME$FUNCNAME*
- `SymbolIsImport` (line 80) `BOOL SymbolIsImport( LPSTR Symbol )`
- `CoffeeProcessSymbol` (line 86) `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )`
- `CoffeeFunction` (line 242) `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )` - *This is our function where we can control/get the return address of it to use it in case of a Veh exception*
- `PUTS` (line 250) `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...`
- `CoffeeCleanup` (line 393) `VOID CoffeeCleanup( PCOFFEE Coffee )`
- `CoffeeProcessSections` (line 423) `BOOL CoffeeProcessSections( PCOFFEE Coffee )` - *Process sections relocation and symbols*
- `CoffeeGetFunMapSize` (line 602) `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )` - *calculate how many __imp_* function there are*
- `RemoveCoffeeFromInstance` (line 641) `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )`
- `PUTS` (line 668) `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...`
- `PRINTF` (line 677) `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...`
- `CoffeeRunnerThread` (line 798) `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )`
- `CoffeeRunner` (line 820) `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...`

**Macros:**
- `COFF_PREP_SYMBOL` (line 12)
- `COFF_PREP_SYMBOL_SIZE` (line 13)
- `COFF_PREP_BEACON` (line 15)
- `COFF_PREP_BEACON_SIZE` (line 16)
- `COFF_INSTANCE` (line 18)
- `COFF_PREP_SYMBOL` (line 21)
- `COFF_PREP_SYMBOL_SIZE` (line 22)
- `COFF_PREP_BEACON` (line 24)
- `COFF_PREP_BEACON_SIZE` (line 25)
- `COFF_INSTANCE` (line 27)

#### `Command.c`
**Path:** `payloads/Demon/src/core/Command.c`

**Functions:**
- `CommandDispatcher` (line 48) `VOID CommandDispatcher( VOID )` - *TODO: rewrite this part and move it into the Demon.c file*
- `PRINTF` (line 107) `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...`
- `PUTS` (line 159) `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )`
- `CommandSleep` (line 173) `VOID CommandSleep( PPARSER Parser )`
- `CommandJob` (line 187) `VOID CommandJob( PPARSER Parser )`
- `CommandProc` (line 262) `VOID CommandProc( PPARSER Parser )`
- `PUTS` (line 272) `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )`
- `PUTS` (line 336) `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")`
- `PUTS` (line 422) `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )`
- `PUTS` (line 467) `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )`
- `PUTS` (line 527) `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )`
- `CommandProcList` (line 562) `VOID CommandProcList(
    IN PPARSER Parser
)` - *! get current list of running processes and sends it back to the server.  TODO: refactor this.  @param Parser*
- `PACKAGE_ERROR_NTSTATUS` (line 671) `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )`
- `PUTS` (line 684) `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )`
- `PUTS` (line 793) `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )`
- `PRINTF` (line 824) `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...`
- `PUTS` (line 865) `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )`
- `PUTS` (line 881) `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )`
- `PUTS` (line 948) `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )`
- `PUTS` (line 963) `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )`
- `PUTS` (line 993) `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )`
- `PUTS` (line 1009) `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )`
- `PUTS` (line 1034) `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )`
- `PUTS` (line 1059) `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )`
- `PUTS` (line 1074) `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )`
- `CommandInlineExecute` (line 1113) `VOID CommandInlineExecute( PPARSER Parser )`
- `PUTS` (line 1181) `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...`
- `CommandInjectDLL` (line 1202) `VOID CommandInjectDLL( PPARSER Parser )`
- `CommandSpawnDLL` (line 1246) `VOID CommandSpawnDLL( PPARSER Parser )`
- `CommandInjectShellcode` (line 1265) `VOID CommandInjectShellcode(
    IN PPARSER Parser
)`
- `PRINTF` (line 1292) `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...`
- `PUTS` (line 1312) `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )`
- `PRINTF` (line 1319) `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...`
- `PUTS` (line 1352) `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )`
- `PUTS` (line 1357) `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )`
- `CommandToken` (line 1372) `VOID CommandToken( PPARSER Parser )`
- `PUTS` (line 1383) `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )`
- `PUTS` (line 1405) `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )`
- `PUTS` (line 1449) `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )`
- `PUTS` (line 1476) `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )`
- `PUTS` (line 1531) `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )`
- `PUTS` (line 1594) `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )`
- `PUTS` (line 1634) `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )`
- `PUTS` (line 1649) `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )`
- `PUTS` (line 1659) `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )`
- `PUTS` (line 1667) `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )`
- `CommandAssemblyInlineExecute` (line 1707) `VOID CommandAssemblyInlineExecute( PPARSER Parser )`
- `PRINTF` (line 1760) `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...`
- `PUTS` (line 1788) `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...`
- `PUTS` (line 1840) `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )`
- `CommandConfig` (line 1864) `VOID CommandConfig( PPARSER Parser )`
- `CommandScreenshot` (line 2083) `VOID CommandScreenshot( PPARSER Parser )`
- `CommandNet` (line 2109) `VOID CommandNet( PPARSER Parser )` - *TODO: The Net module is unstable so fix those issues to work on normal workstation and domain server*
- `PUTS` (line 2350) `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )`
- `CommandPivot` (line 2462) `VOID CommandPivot( PPARSER Parser )`
- `CommandTransfer` (line 2607) `VOID CommandTransfer( PPARSER Parser )`
- `PUTS` (line 2624) `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )`
- `PUTS` (line 2640) `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )`
- `PUTS` (line 2667) `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )`
- `PUTS` (line 2695) `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )`
- `CommandSocket` (line 2738) `VOID CommandSocket( PPARSER Parser )`
- `PUTS` (line 2751) `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )`
- `PUTS` (line 2785) `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )`
- `PUTS` (line 2818) `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )`
- `PUTS` (line 2849) `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )`
- `PUTS` (line 2870) `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )`
- `PUTS` (line 2877) `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )`
- `PUTS` (line 2941) `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )`
- `PRINTF` (line 2996) `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...`
- `PUTS` (line 3035) `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )`
- `CommandKerberos` (line 3076) `VOID CommandKerberos(
    IN PPARSER Parser
)`
- `PUTS` (line 3090) `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")`
- `PUTS` (line 3116) `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")`
- `PUTS` (line 3204) `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")`
- `PUTS` (line 3215) `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")`
- `CommandMemFile` (line 3236) `VOID CommandMemFile( PPARSER Parser )`
- `InWorkingHours` (line 3262) `BOOL InWorkingHours( )`
- `ReachedKillDate` (line 3294) `BOOL ReachedKillDate()`
- `KillDate` (line 3299) `VOID KillDate( )`
- `CommandExit` (line 3315) `VOID CommandExit( PPARSER Parser )` - *TODO: rewrite this. disconnect all pivots. kill our threads. release memory and free itself.*

#### `Dotnet.c`
**Path:** `payloads/Demon/src/core/Dotnet.c`

**Functions:**
- `DotnetExecute` (line 18) `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )`
- `PUTS` (line 100) `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...`
- `PUTS` (line 112) `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...`
- `PUTS` (line 120) `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...` - *ThreadId = U_PTR( Instance->Teb->ClientId.UniqueThread ); /* add Amsi bypass if ( AmsiIsLoaded ) { PUTS( "HwBp Engine add AmsiScanBuffer bypass" ) ...*
- `PUTS` (line 147) `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...`
- `PUTS` (line 153) `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...`
- `PRINTF` (line 169) `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...`
- `PUTS` (line 178) `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...`
- `PUTS` (line 236) `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...`
- `PUTS` (line 285) `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...`
- `DotnetPushPipe` (line 312) `VOID DotnetPushPipe()` - *} else PUTS( "NtAlertResumeThread failed" ) } else PUTS( "NtGetThreadContext failed" ) } else PUTS( "NtCreateThreadEx failed" ) } else PUTS( "NtCre...*
- `DotnetPush` (line 346) `VOID DotnetPush()`
- `PRINTF` (line 351) `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...`
- `DotnetClose` (line 378) `VOID DotnetClose()`
- `PUTS` (line 427) `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )`
- `PUTS` (line 435) `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )`
- `FindVersion` (line 500) `BOOL FindVersion( PVOID Assembly, DWORD length )`
- `ClrCreateInstance` (line 523) `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...`

**Macros:**
- `PIPE_BUFFER` (line 7)

#### `Download.c`
**Path:** `payloads/Demon/src/core/Download.c`

**Functions:**
- `DownloadAdd` (line 6) `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )` - *#include <Demon.h> #include <core/MiniStd.h> /* Add file to linked list with type (upload/download)*
- `DownloadGet` (line 27) `PDOWNLOAD_DATA DownloadGet( DWORD FileID )` - *Download->Size      = MaxSize; Download->State     = DOWNLOAD_STATE_RUNNING; Download->Next      = Instance->Downloads; Download->RequestID = Insta...*
- `DownloadFree` (line 41) `VOID DownloadFree( PDOWNLOAD_DATA Download )` - *PDOWNLOAD_DATA DownloadGet( DWORD FileID ) { PDOWNLOAD_DATA Download = NULL; for ( Download = Instance->Downloads; Download == NULL; Download = Dow...*
- `DownloadRemove` (line 55) `BOOL DownloadRemove( DWORD FileID )`
- `DownloadPush` (line 94) `VOID DownloadPush()` - */* return that we succeeded. Success = TRUE; break; } Last     = Download; Download = Download->Next; } return Success; } /* send file chunks to te...*
- `PRINTF` (line 128) `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...`
- `MemFileIsNew` (line 237) `BOOL MemFileIsNew( ULONG32 ID )`
- `NewMemFile` (line 254) `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` - *PMEM_FILE MemFile = Instance->MemFiles; while ( MemFile ) { if ( MemFile->ID == ID ) return FALSE; MemFile = MemFile->Next; } return TRUE; } /* Add...*
- `GetMemFile` (line 286) `PMEM_FILE GetMemFile( ULONG32 ID )`
- `ProcessMemFileChunk` (line 301) `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- `MemFileReadChunk` (line 317) `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- `MemFileFree` (line 338) `VOID MemFileFree( PMEM_FILE MemFile )`
- `RemoveMemFile` (line 354) `BOOL RemoveMemFile( ULONG32 ID )`

#### `HwBpEngine.c`
**Path:** `payloads/Demon/src/core/HwBpEngine.c`

**Functions:**
- `HwBpEngineInit` (line 18) `NTSTATUS HwBpEngineInit(
    OUT PHWBP_ENGINE Engine,
    IN  PVOID        Handler
)` - *! Init Hardware breakpoint engine by registering a Vectored exception handler @param Engine   if empty global handler gonna be used @param Handler ...*
- `HwBpEngineSetBp` (line 61) `NTSTATUS HwBpEngineSetBp(
    IN DWORD Tid,
    IN PVOID Address,
    IN BYTE  Position,
    IN B...` - *! Set hardware breakpoint on specified address @param Tib @param Address @param Position @param Add @return*
- `PRINTF` (line 115) `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...`
- `HwBpEngineAdd` (line 152) `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...` - *! Set an hardware breakpoint to an address and adds it to the engine breakpoints list linked @param Engine @param Thread @param Address @param Func...*
- `PRINTF` (line 161) `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...`
- `HwBpEngineRemove` (line 208) `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...`
- `HwBpEngineDestroy` (line 260) `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)`
- `ExceptionHandler` (line 320) `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)` - *! Global exception handler @param Exception @return*
- `PRINTF` (line 354) `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )`

#### `HwBpExceptions.c`
**Path:** `payloads/Demon/src/core/HwBpExceptions.c`

**Functions:**
- `HwBpExAmsiScanBuffer` (line 5) `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)` - *if _WIN64*
- `HwBpExNtTraceEvent` (line 22) `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)`

#### `Jobs.c`
**Path:** `payloads/Demon/src/core/Jobs.c`

**Functions:**
- `JobAdd` (line 17) `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )` - *! JobAdd Adds a job to the job linked list @param JobID @param Type type of job: thread or process @param State current state of the job: suspended...*
- `JobCheckList` (line 63) `VOID JobCheckList()` - *! Check if all jobs are still running and exists @return*
- `JobSuspend` (line 184) `BOOL JobSuspend( DWORD JobID )` - *! JobSuspend Suspends the specified job @param JobID @return*
- `PRINTF` (line 192) `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- `JobResume` (line 230) `BOOL JobResume( DWORD JobID )` - *! JobSuspend Suspends the specified job @param JobID @return*
- `PRINTF` (line 238) `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- `JobKill` (line 277) `BOOL JobKill( DWORD JobID )` - *! JobKill Kills and remove the specified job @param JobID @return*
- `PRINTF` (line 287) `PRINTF( "Found Job ID: %d\n", JobID )

            switch ( JobList->Type )`
- `PUTS` (line 300) `PUTS( "Kill using handle" )

                            if ( ! NT_SUCCESS( NtStatus = Instance->...`
- `JobRemove` (line 383) `VOID JobRemove( DWORD JobID )` - *! JobRemove Remove the specified job @param ThreadID @return*

#### `Kerberos.c`
**Path:** `payloads/Demon/src/core/Kerberos.c`

**Functions:**
- `IsHighIntegrity` (line 7) `BOOL IsHighIntegrity(HANDLE TokenHandle)` - *include <Demon.h> include <core/Kerberos.h> include <core/Win32.h> include <core/MiniStd.h> include <core/Token.h>*
- `GetProcessIdByName` (line 28) `DWORD GetProcessIdByName(WCHAR* processName)`
- `ElevateToSystem` (line 60) `BOOL ElevateToSystem()`
- `IsSystem` (line 130) `BOOL IsSystem( HANDLE TokenHandle )`
- `GetLsaHandle` (line 154) `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )`
- `GetLogonSessionData` (line 217) `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )`
- `ExtractTicket` (line 282) `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...`
- `CopySessionInfo` (line 336) `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )`
- `CopyTicketInfo` (line 370) `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )`
- `Ptt` (line 398) `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )`
- `Purge` (line 493) `BOOL Purge( HANDLE hToken, LUID luid )`
- `Klist` (line 584) `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )`
- `GetLUID` (line 751) `LUID* GetLUID( HANDLE hToken )`

#### `Memory.c`
**Path:** `payloads/Demon/src/core/Memory.c`

**Functions:**
- `MmHeapAlloc` (line 15) `PVOID MmHeapAlloc(
    _In_ ULONG Length
)` - *! @brief allocate memory on the heap  @param Length size of memory to allocate  @return allocated buffer pointer on the heap*
- `MmHeapReAlloc` (line 31) `PVOID MmHeapReAlloc(
    _In_ PVOID Memory,
    _In_ ULONG Length
)` - *! @brief allocate memory on the heap  @param Length size of memory to reallocate  @return allocated buffer pointer on the heap*
- `MmHeapFree` (line 48) `BOOL MmHeapFree(
    _In_ PVOID Memory
)` - *! @brief free memory on the heap  @param Memory memory to free  @return if successfully freed memory on the heap*
- `MmVirtualAlloc` (line 62) `PVOID MmVirtualAlloc(
    IN DX_MEMORY Methode,
    IN HANDLE    Process,
    IN SIZE_T    Size,
...` - *! Allocates virtual memory @param Method @param Process @param Size @param Protect @return*
- `PUTS` (line 79) `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- `MmVirtualProtect` (line 133) `BOOL MmVirtualProtect(
    IN DX_MEMORY Method,
    IN HANDLE    Process,
    IN PVOID     Memory...` - *! Changes the protection of a virtual memory. @param Method @param Process @param Memory @param Size @param Protect @return*
- `PUTS` (line 147) `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- `MmVirtualWrite` (line 188) `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...`
- `MmVirtualFree` (line 209) `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)` - *! Frees virtual memory @param Process @param Memory @return*
- `MmGadgetFind` (line 239) `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...`
- `FreeReflectiveLoader` (line 269) `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)` - *! Frees the reflective loader @param BaseAddress @return*

#### `MiniStd.c`
**Path:** `payloads/Demon/src/core/MiniStd.c`

**Functions:**
- `StringCompareA` (line 8) `INT StringCompareA( LPCSTR String1, LPCSTR String2 )` - *Most of the functions from here are from VX-Underground https://github.com/vxunderground/VX-API*
- `StringCompareW` (line 20) `INT StringCompareW( LPWSTR String1, LPWSTR String2 )`
- `StringNCompareW` (line 32) `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )`
- `ToLowerCaseW` (line 47) `WCHAR ToLowerCaseW( WCHAR C )`
- `StringCompareIW` (line 52) `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )`
- `StringNCompareIW` (line 64) `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )`
- `EndsWithIW` (line 79) `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )`
- `HashStringA` (line 100) `DWORD HashStringA( PCHAR String )` - *return FALSE; Length1 = StringLengthW( String ); Length2 = StringLengthW( Ending ); if ( Length1 < Length2 ) return FALSE; String = &String[ Length...*
- `StringCopyA` (line 110) `PCHAR StringCopyA(PCHAR String1, PCHAR String2)`
- `StringCopyW` (line 120) `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)`
- `StringLengthA` (line 129) `SIZE_T StringLengthA(LPCSTR String)`
- `StringLengthW` (line 141) `SIZE_T StringLengthW(LPCWSTR String)`
- `StringConcatA` (line 150) `PCHAR StringConcatA(PCHAR String, PCHAR String2)`
- `StringConcatW` (line 157) `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)`
- `WcsStr` (line 164) `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )`
- `WcsIStr` (line 184) `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )`
- `MemCompare` (line 204) `INT MemCompare( PVOID s1, PVOID s2, INT len)`
- `WCharStringToCharString` (line 228) `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)`
- `CharStringToWCharString` (line 241) `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
- `StringTokenA` (line 254) `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)`
- `GetSystemFileTime` (line 299) `UINT64 GetSystemFileTime( )`
- `HideChar` (line 313) `BYTE NO_INLINE HideChar( BYTE C )` - *UINT64 GetSystemFileTime( ) { FILETIME ft; LARGE_INTEGER li; Instance->Win32.GetSystemTimeAsFileTime(&ft); //returns ticks in UTC li.LowPart  = ft....*

#### `Obf.c`
**Path:** `payloads/Demon/src/core/Obf.c`

**Functions:**
- `FoliageObf` (line 22) `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)` - *! @brief foliage is a sleep obfuscation technique that is using APC calls to obfuscate itself in memory  @param Param @return*
- `PRINTF` (line 603) `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...`
- `SleepTime` (line 649) `UINT32 SleepTime(
    VOID
)` - *endif*
- `SleepObf` (line 713) `VOID SleepObf(
    VOID
)`

#### `ObjectApi.c`
**Path:** `payloads/Demon/src/core/ObjectApi.c`

**Functions:**
- `LdrModulePebString` (line 20) `PVOID LdrModulePebString( PCHAR ModuleString )` - *Meh some wrapper functions for internal demon GetProcAddress and GetModuleHandleA functions.*
- `LdrFunctionAddrString` (line 25) `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )`
- `LdrFreeLibrary` (line 31) `BOOL LdrFreeLibrary( HMODULE hLibModule )`
- `LdrLocalFree` (line 36) `HLOCAL LdrLocalFree( PVOID hMem )`
- `swap_endianess` (line 130) `uint32_t swap_endianess(uint32_t indata)`
- `BeaconDataParse` (line 142) `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )`
- `BeaconDataInt` (line 154) `INT BeaconDataInt( PDATA parser )`
- `BeaconDataShort` (line 169) `SHORT BeaconDataShort( datap* parser )`
- `BeaconDataLength` (line 184) `INT BeaconDataLength( PDATA parser )`
- `BeaconDataExtract` (line 189) `PCHAR BeaconDataExtract( PDATA parser, PINT size )`
- `GetRequestIDForCallingObjectFile` (line 224) `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )` - *This function is called by BeaconPrintf and BeaconOutput. It loops over all the COFFEE structs saved on the Instance object trying to find which BO...*
- `BeaconPrintf` (line 247) `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )`
- `BeaconOutput` (line 304) `VOID BeaconOutput( INT Type, PCHAR data, INT len )`
- `BeaconIsAdmin` (line 323) `BOOL BeaconIsAdmin(
    VOID
)`
- `BeaconFormatAlloc` (line 342) `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )`
- `BeaconFormatReset` (line 353) `VOID BeaconFormatReset( PFORMAT format )`
- `BeaconFormatFree` (line 360) `VOID BeaconFormatFree( PFORMAT format )`
- `BeaconFormatAppend` (line 376) `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )`
- `BeaconFormatPrintf` (line 383) `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )`
- `BeaconFormatToString` (line 404) `char* BeaconFormatToString( PFORMAT format, int* size)`
- `BeaconFormatInt` (line 410) `VOID BeaconFormatInt( PFORMAT format, int value)`
- `BeaconUseToken` (line 424) `BOOL BeaconUseToken( HANDLE token )`
- `BeaconGetSpawnTo` (line 439) `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )`
- `BeaconSpawnTemporaryProcess` (line 462) `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...`
- `BeaconInjectProcess` (line 486) `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...`
- `BeaconInjectTemporaryProcess` (line 529) `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...`
- `BeaconCleanupProcess` (line 563) `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )`
- `BeaconInformation` (line 578) `VOID BeaconInformation(BEACON_INFO * info)` - *not implemented*
- `BeaconAddValue` (line 583) `BOOL BeaconAddValue(const char * key, void * ptr)`
- `BeaconGetValue` (line 632) `PVOID BeaconGetValue(const char * key)`
- `BeaconRemoveValue` (line 655) `BOOL BeaconRemoveValue(const char * key)`
- `BeaconDataStoreGetItem` (line 690) `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)` - *not implemented*
- `BeaconDataStoreProtectItem` (line 697) `VOID BeaconDataStoreProtectItem(SIZE_T index)` - *not implemented*
- `BeaconDataStoreUnprotectItem` (line 704) `VOID BeaconDataStoreUnprotectItem(SIZE_T index)` - *not implemented*
- `BeaconDataStoreMaxEntries` (line 711) `SIZE_T BeaconDataStoreMaxEntries()` - *not implemented*
- `BeaconGetCustomUserData` (line 718) `PCHAR BeaconGetCustomUserData()` - *not implemented*
- `toWideChar` (line 723) `BOOL toWideChar( char* src, wchar_t* dst, int max )`

**Macros:**
- `bufsize` (line 16)

#### `Package.c`
**Path:** `payloads/Demon/src/core/Package.c`

**Functions:**
- `Int64ToBuffer` (line 12) `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )` - */* Import Core Headers #include <core/Package.h> #include <core/MiniStd.h> #include <core/Command.h> #include <core/Transport.h> #include <core/Tra...*
- `Int32ToBuffer` (line 38) `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)`
- `PackageAddInt32` (line 48) `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)`
- `PackageAddInt64` (line 67) `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )`
- `PackageAddBool` (line 84) `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)`
- `PackageAddPtr` (line 103) `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )`
- `PackageAddPad` (line 108) `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )`
- `PackageAddBytes` (line 124) `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )`
- `PackageAddString` (line 146) `VOID PackageAddString( PPACKAGE package, PCHAR data )`
- `PackageAddWString` (line 151) `VOID PackageAddWString( PPACKAGE package, PWCHAR data )`
- `PackageCreate` (line 156) `PPACKAGE PackageCreate( UINT32 CommandID )`
- `PackageCreateWithMetaData` (line 173) `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )`
- `PackageCreateWithRequestID` (line 186) `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )`
- `PackageDestroy` (line 195) `VOID PackageDestroy(
    IN PPACKAGE Package
)`
- `PackageTransmitNow` (line 229) `BOOL PackageTransmitNow(
    _Inout_ PPACKAGE Package,
    OUT    PVOID*   Response,
    OUT    P...` - *used to send the demon's metadata*
- `PUTS_DONT_SEND` (line 264) `PUTS_DONT_SEND("TransportSend failed!")
        }

        if ( Package->Destroy )`
- `PackageTransmit` (line 281) `VOID PackageTransmit(
    IN PPACKAGE Package
)` - *don't transmit right away, simply store the package. Will be sent when PackageTransmitAll is called*
- `PackageTransmitAll` (line 333) `BOOL PackageTransmitAll(
    OUT    PVOID*   Response,
    OUT    PSIZE_T  Size
)` - *transmit all stored packages in a single request*
- `PackageTransmitError` (line 470) `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)`

**Macros:**
- `CTR` (line 9)
- `AES256` (line 10)

#### `Parser.c`
**Path:** `payloads/Demon/src/core/Parser.c`

**Functions:**
- `ParserNew` (line 6) `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )` - *include <core/Parser.h> include <core/MiniStd.h> include <crypt/AesCrypt.h>*
- `ParserDecrypt` (line 20) `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )`
- `ParserGetInt16` (line 31) `INT16 ParserGetInt16( PPARSER parser )`
- `ParserGetByte` (line 47) `BYTE ParserGetByte( PPARSER parser )`
- `ParserGetInt32` (line 62) `INT ParserGetInt32( PPARSER parser )`
- `ParserGetInt64` (line 84) `INT64 ParserGetInt64( PPARSER parser )`
- `ParserGetBool` (line 105) `BOOL ParserGetBool( PPARSER parser )`
- `ParserGetBytes` (line 126) `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )`
- `ParserGetString` (line 157) `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )`
- `ParserGetWString` (line 162) `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )`
- `ParserDestroy` (line 167) `VOID ParserDestroy( PPARSER Parser )`

#### `Pivot.c`
**Path:** `payloads/Demon/src/core/Pivot.c`

**Functions:**
- `PivotAdd` (line 23) `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )` - *TODO: Change the way new pivots gets added.  Instead of appending it to the newest token like: PivotNew->Next = Pivot  Add it to the first token (p...*
- `PivotGet` (line 120) `PPIVOT_DATA PivotGet( DWORD AgentID )`
- `PivotRemove` (line 138) `BOOL PivotRemove( DWORD AgentId )`
- `PivotCount` (line 217) `DWORD PivotCount()`
- `PivotPush` (line 234) `VOID PivotPush()`
- `PivotParseDemonID` (line 330) `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )`

#### `Runtime.c`
**Path:** `payloads/Demon/src/core/Runtime.c`

**Functions:**
- `RtAdvapi32` (line 4) `BOOL RtAdvapi32(
    VOID
)` - *include <Demon.h> include <core/Runtime.h> include <core/MiniStd.h>*
- `RtMscoree` (line 68) `BOOL RtMscoree(
    VOID
)` - *we delay loading mscoree.dll*
- `RtOleaut32` (line 102) `BOOL RtOleaut32(
    VOID
)`
- `RtUser32` (line 141) `BOOL RtUser32(
    VOID
)`
- `RtShell32` (line 175) `BOOL RtShell32(
    VOID
)`
- `RtMsvcrt` (line 207) `BOOL RtMsvcrt(
    VOID
)`
- `RtIphlpapi` (line 239) `BOOL RtIphlpapi(
    VOID
)`
- `RtGdi32` (line 272) `BOOL RtGdi32(
    VOID
)`
- `RtNetApi32` (line 309) `BOOL RtNetApi32(
    VOID
)`
- `RtWs2_32` (line 348) `BOOL RtWs2_32(
    VOID
)`
- `RtSspicli` (line 392) `BOOL RtSspicli(
    VOID
)`
- `RtAmsi` (line 432) `BOOL RtAmsi(
    VOID
)`
- `RtWinHttp` (line 463) `BOOL RtWinHttp(
    VOID
)` - *ifdef TRANSPORT_HTTP*

#### `Socket.c`
**Path:** `payloads/Demon/src/core/Socket.c`

**Functions:**
- `RecvAll` (line 7) `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )` - *attempt to receive all the requested data from the socket * Took it from: https://github.com/rsmudge/metasploit-loader/blob/master/src/main.c#L41*
- `InitWSA` (line 32) `BOOL InitWSA( VOID )`
- `PUTS` (line 41) `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...`
- `SocketNew` (line 59) `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...` - *PRINTF( "WSAStartup Failed: %d\n", Result ) /* cleanup and be gone. Instance->Win32.WSACleanup(); return FALSE; } Instance->WSAWasInitialised = TRU...*
- `PUTS` (line 73) `PUTS( "Create Socket..." )

        if ( UseIpv4 )`
- `PRINTF` (line 111) `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...`
- `SocketClients` (line 213) `VOID SocketClients()` - *CLEANUP: if ( WinSock && WinSock != INVALID_SOCKET ) { close the socket preserving the last error code ErrorCode = NtGetLastError(); Instance->Win3...*
- `SocketRead` (line 281) `VOID SocketRead()` - *{ PRINTF( "ioctlsocket failed: %d\n", NtGetLastError() ) /* close socket. Instance->Win32.closesocket( WinSock ); } } } Socket = Socket->Next; } } ...*
- `SocketFree` (line 424) `VOID SocketFree( PSOCKET_DATA Socket )`
- `PRINTF` (line 428) `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...`
- `SocketCleanDead` (line 481) `VOID SocketCleanDead()`
- `SocketPush` (line 521) `VOID SocketPush()`
- `DnsQueryIPv4` (line 539) `DWORD DnsQueryIPv4( LPSTR Domain )` - *! Query the IPv4 from the specified domain @param Domain @return IPv4 address*
- `DnsQueryIPv6` (line 580) `PBYTE DnsQueryIPv6( LPSTR Domain )` - *! Query the IPv6 from the specified domain @param Domain @return IPv6 address*

#### `Spoof.c`
**Path:** `payloads/Demon/src/core/Spoof.c`

**Functions:**
- `SpoofRetAddr` (line 5) `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...` - *if _WIN64*

#### `SysNative.c`
**Path:** `payloads/Demon/src/core/SysNative.c`

**Functions:**
- `SysNtOpenThread` (line 5) `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...` - *include <core/Syscalls.h> include <core/SysNative.h>*
- `SysNtOpenProcess` (line 19) `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...`
- `SysNtTerminateProcess` (line 33) `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...`
- `SysNtOpenThreadToken` (line 45) `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...`
- `SysNtOpenProcessToken` (line 59) `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...`
- `SysNtDuplicateToken` (line 72) `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...`
- `SysNtQueueApcThread` (line 88) `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...`
- `SysNtSuspendThread` (line 103) `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...`
- `SysNtResumeThread` (line 115) `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...`
- `SysNtCreateEvent` (line 127) `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...`
- `SysNtCreateThreadEx` (line 142) `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...`
- `SysNtDuplicateObject` (line 175) `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...`
- `SysNtGetContextThread` (line 192) `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...`
- `SysNtSetContextThread` (line 204) `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)`
- `SysNtQueryInformationProcess` (line 216) `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...`
- `SysNtQuerySystemInformation` (line 231) `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...`
- `SysNtWaitForSingleObject` (line 245) `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...`
- `SysNtAllocateVirtualMemory` (line 258) `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...`
- `SysNtWriteVirtualMemory` (line 274) `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...`
- `SysNtFreeVirtualMemory` (line 289) `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...`
- `SysNtUnmapViewOfSection` (line 303) `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)`
- `SysNtProtectVirtualMemory` (line 315) `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...`
- `SysNtReadVirtualMemory` (line 330) `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...`
- `SysNtTerminateThread` (line 345) `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...`
- `SysNtAlertResumeThread` (line 357) `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...`
- `SysNtSignalAndWaitForSingleObject` (line 369) `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...`
- `SysNtQueryVirtualMemory` (line 383) `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...`
- `SysNtQueryInformationToken` (line 399) `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...`
- `SysNtQueryInformationThread` (line 414) `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...`
- `SysNtQueryObject` (line 429) `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...`
- `SysNtClose` (line 444) `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)`
- `SysNtSetInformationThread` (line 455) `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...`
- `SysNtSetInformationVirtualMemory` (line 469) `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...`
- `SysNtGetNextThread` (line 485) `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...`

#### `Syscalls.c`
**Path:** `payloads/Demon/src/core/Syscalls.c`

**Functions:**
- `SysInitialize` (line 12) `BOOL SysInitialize(
    IN PVOID Ntdll
)` - *! Initialize syscall addr + ssn @param Ntdll @return*
- `SYS_EXTRACT` (line 44) `SYS_EXTRACT( NtOpenThread )
    SYS_EXTRACT( NtOpenThreadToken )
    SYS_EXTRACT( NtOpenProcess )...` - *Instance->Syscall.SysAddress = SysIndirectAddr; } else { PUTS_DONT_SEND( "Failed to resolve SysIndirectAddr" ); } } #if _M_IX86 if ( IsWoW64() ) { ...*
- `PRINTF` (line 184) `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )
        }

        if ( Sys...`
- `FindSsnOfHookedSyscall` (line 201) `BOOL FindSsnOfHookedSyscall(
    IN  PVOID  Function,
    OUT PWORD  Ssn
)` - *If a function is hooked, we can't obtain the Ssn directly. Instead, we look for the Ssn of a neighbouring syscalls and add/subtract to their Ssn ac...*
- `PRINTF` (line 208) `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...`

#### `Thread.c`
**Path:** `payloads/Demon/src/core/Thread.c`

**Functions:**
- `ThreadQueryTib` (line 20) `BOOL ThreadQueryTib(
    IN  PVOID   Adr,
    OUT PNT_TIB Tib
)` - *! queries the NT_TIB from the specified leaked thread RSP address  NOTE: this function is entirely taken from Austins Hudson's implementation. refe...*
- `ThreadCreateWoW64` (line 118) `HANDLE ThreadCreateWoW64(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  PVOID  Entry,
  ...` - *https://github.com/rapid7/meterpreter/blob/5e309596e53ead0f64564fe77e0cad70908f6739/source/common/arch/win/i386/base_inject.c#L343*
- `PUTS` (line 184) `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...`
- `ThreadCreate` (line 216) `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...` - *endif*

#### `Token.c`
**Path:** `payloads/Demon/src/core/Token.c`

**Functions:**
- `TokenDuplicate` (line 37) `BOOL TokenDuplicate(
    IN  HANDLE        TokenOriginal,
    IN  DWORD         Access,
    IN  S...` - *! @brief Duplicate given token  @param TokenOriginal @param Access @param ImpersonateLevel @param TokenType @param TokenNew @return*
- `TokenRevSelf` (line 74) `BOOL TokenRevSelf(
    VOID
)` - *! @brief reverse to the original process user token  @return if successful reverse to original token*
- `TokenQueryOwner` (line 103) `BOOL TokenQueryOwner(
    IN  HANDLE  Token,
    OUT PBUFFER UserDomain,
    IN  DWORD   Flags
)` - *! @brief queries the username and or domain  @note the queried memory should be freed after used using HeapFree/RtlFreeHeap  @param Token @param Us...*
- `PUTS` (line 177) `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )
    }

LEAVE:
    if ( UserInfo )`
- `DATA_FREE` (line 182) `DATA_FREE( UserInfo, UserSize )
    }

    if ( Flags == TOKEN_OWNER_FLAG_USER )`
- `TokenSetPrivilege` (line 203) `BOOL TokenSetPrivilege(
    IN LPSTR Privilege,
    IN BOOL  Enable
)` - *! sets a privilege  TODO: change it to use wide strings.  @param Privilege @param Enable @return*
- `TokenSetSeDebugPriv` (line 239) `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)`
- `TokenSetSeImpersonatePriv` (line 270) `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)`
- `TokenAdd` (line 323) `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...` - *Adds an token to the vault.  TODO: rewrite the function param. accept token object + STOLEN PID or MAKE data as a struct.  @param hToken @param Dom...*
- `SysDuplicateTokenEx` (line 364) `BOOL SysDuplicateTokenEx(
    IN HANDLE ExistingTokenHandle,
    IN DWORD dwDesiredAccess,
    IN...`
- `TokenSteal` (line 414) `HANDLE TokenSteal(
    IN DWORD  ProcessID,
    IN HANDLE TargetHandle
)` - *! Steals the process token from the specified pid @param ProcessID @param TargetHandle @return*
- `PRINTF` (line 463) `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
    }

    ...`
- `TokenRemove` (line 473) `BOOL TokenRemove( DWORD TokenID )`
- `TokenMake` (line 597) `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )`
- `PRINTF` (line 601) `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...`
- `PRINTF` (line 606) `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...`
- `TokenCurrentHandle` (line 624) `HANDLE TokenCurrentHandle(
    VOID
)` - *! get current process/thread token @return*
- `TokenElevated` (line 649) `BOOL TokenElevated(
    IN HANDLE Token
)`
- `TokenGet` (line 663) `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)`
- `TokenClear` (line 680) `VOID TokenClear(
    VOID
)`
- `TokenImpersonate` (line 706) `BOOL TokenImpersonate(
    IN BOOL Impersonate
)`
- `AddUserToken` (line 732) `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...`
- `IsImpersonationToken` (line 770) `BOOL IsImpersonationToken( HANDLE token )`
- `CanTokenBeImpersonated` (line 802) `BOOL CanTokenBeImpersonated( IN HANDLE hToken )` - *https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/extensions/incognito/list_tokens.c*
- `ProcessUserToken` (line 829) `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...`
- `QueryObjectTypesInfo` (line 878) `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )` - *call NtQueryObject with ObjectTypesInformation*
- `GetTypeIndexToken` (line 910) `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )` - *get index of object type 'Token'*
- `GetTokenInfo` (line 948) `BOOL GetTokenInfo(
    IN HANDLE hToken,
    OUT PDWORD pTokenType,
    OUT PDWORD pIntegrity,
  ...`
- `PUTS` (line 991) `PUTS( "GetTokenInformation failed" )
            }
        }
        else if (TokenStatisticsInfo...`
- `ProcessIsIncluded` (line 1029) `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )` - *check if a PID is included in the process list*
- `GetProcessesFromHandleTable` (line 1040) `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...` - *obtain a list of PIDs from a handle table*
- `GetAllHandles` (line 1076) `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )` - *get all handles in the system*
- `IsNotCurrentUser` (line 1122) `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )` - *phandle_table = (PSYSTEM_HANDLE_INFORMATION)handleTableInformation; phandle_table_size = buffer_size; ret_val = TRUE; cleanup: if ( ! ret_val && ha...*
- `ListTokens` (line 1129) `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )`
- `ImpersonateTokenFromVault` (line 1256) `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)`
- `SysImpersonateLoggedOnUser` (line 1281) `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )` - *https://doxygen.reactos.org/d1/d72/dll_2win32_2advapi32_2sec_2misc_8c_source.html#l00152*
- `ImpersonateTokenInStore` (line 1360) `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)`

#### `Transport.c`
**Path:** `payloads/Demon/src/core/Transport.c`

**Functions:**
- `TransportInit` (line 12) `BOOL TransportInit( )` - *include <crypt/AesCrypt.h>*
- `TransportSend` (line 51) `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )`
- `SMBGetJob` (line 88) `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )` - *ifdef TRANSPORT_SMB*

#### `TransportHttp.c`
**Path:** `payloads/Demon/src/core/TransportHttp.c`

**Functions:**
- `HttpSend` (line 21) `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)` - *! @brief send a http request  @param Send buffer to send  @param Resp buffer response  @return if successful send request*
- `PRINTF_DONT_SEND` (line 290) `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )`
- `HttpQueryStatus` (line 336) `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)` - *! @brief Query the Http Status code from the request response.  @param hRequest request handle  @return Http status code*
- `HostAdd` (line 355) `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )`
- `HostFailure` (line 377) `PHOST_DATA HostFailure( PHOST_DATA Host )`
- `HostRandom` (line 402) `PHOST_DATA HostRandom()` - */* Get our next host based on our rotation strategy. return HostRotation( Instance->Config.Transport.HostRotation ); } /* Increase our failed count...*
- `HostRotation` (line 436) `PHOST_DATA HostRotation( SHORT Strategy )`
- `HostCount` (line 513) `DWORD HostCount()`
- `HostCheckup` (line 540) `BOOL HostCheckup()`

#### `TransportSmb.c`
**Path:** `payloads/Demon/src/core/TransportSmb.c`

**Functions:**
- `SmbSend` (line 7) `BOOL SmbSend( PBUFFER Send )` - *ifdef TRANSPORT_SMB*
- `SmbRecv` (line 64) `BOOL SmbRecv( PBUFFER Resp )`
- `PRINTF` (line 107) `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...`
- `SmbSecurityAttrOpen` (line 142) `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )` - *Took it from https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/metsrv/server_pivot_named_pipe.c#L286 * But seems like ...*
- `SmbSecurityAttrFree` (line 212) `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )`

#### `Win32.c`
**Path:** `payloads/Demon/src/core/Win32.c`

**Functions:**
- `HashEx` (line 17) `ULONG HashEx(
    IN PVOID String,
    IN ULONG Length,
    IN BOOL  Upper
)` - *! Extended String Hasher @param String @param Length @param Upper @return*
- `LdrModulePeb` (line 65) `PVOID LdrModulePeb(
    IN DWORD Hash
)` - *! load module from PEB InLoadOrderModuleList by Hash @param Hash @return*
- `LdrModulePebByString` (line 99) `PVOID LdrModulePebByString(
    IN LPWSTR Module
)` - *! load module from PEB InLoadOrderModuleList by String @param Module name of module (needs to be upper case: MODULE.DLL) @return*
- `LdrModuleSearch` (line 165) `PVOID LdrModuleSearch(
    IN LPWSTR ModuleName)` - *! Search for a DLL on the PEB module list  @param ModuleName module name @return*
- `LdrModuleLoad` (line 215) `PVOID LdrModuleLoad(
    IN LPSTR ModuleName
)` - *! Load Library by string name.  @note based on how it is configured to load the module it either proxy calls LoadLibraryW using RtlRegisterWait/Rtl...*
- `PUTS` (line 252) `PUTS( "Loading module using RtlRegisterWait" )

            /* create an event for end of module ...`
- `PUTS` (line 269) `PUTS( "Loading module using RtlCreateTimer" )

            /* create timer queue */
            i...`
- `PUTS` (line 286) `PUTS( "Loading module using RtlQueueWorkItem" )

            /* call LoadLibraryW and load specif...`
- `PRINTF` (line 353) `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

    /* close event end */
    if ( Event )`
- `LdrFunctionAddr` (line 377) `PVOID LdrFunctionAddr(
    IN PVOID Module,
    IN DWORD Hash
)` - *! gets the function pointer @param Module @param FunctionHash @return*
- `GetSyscallSize` (line 440) `UINT32 GetSyscallSize(
    VOID
)` - *Get the size of an NtApi by finding two consecutive syscalls and returning the difference of their addresses. This can't be static because it chang...*
- `ProcessOpen` (line 515) `HANDLE ProcessOpen(
    IN DWORD Pid,
    IN DWORD Access
)` - *! opens a handle to the specified pid with specified access @param ProcessID @param Access @return*
- `ProcessIsWow` (line 544) `BOOL ProcessIsWow(
    IN HANDLE Process
)` - *! checks if a process runs under Wow64 @param Process @return*
- `ProcessCreate` (line 579) `BOOL ProcessCreate(
    IN  BOOL                 x86,
    IN  LPWSTR               App,
    IN  L...` - *! Starts a Process  @param x86 start 32-bit/wow64 process @param App App path @param CmdLine Process to run @param Flags Process Flags @param Proce...*
- `PUTS` (line 626) `PUTS( "Enable Wow64 process support" )
        if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...`
- `PRINTF` (line 653) `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...`
- `PUTS` (line 670) `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...`
- `PUTS` (line 693) `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...`
- `PUTS` (line 739) `PUTS( "Send info back" )
        if ( ! CmdLine )`
- `ProcessTerminate` (line 805) `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)`
- `PUTS` (line 831) `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )`
- `ProcessSnapShot` (line 848) `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...` - *! takes a snapshot of current running processes @param SnapShot @param Size @return*
- `ReadLocalFile` (line 885) `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...`
- `BypassPatchAMSI` (line 930) `BOOL BypassPatchAMSI(
    VOID
)` - *Patch AMSI * TODO: remove this and replace it with hardware breakpoints*
- `AnonPipesInit` (line 980) `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)`
- `AnonPipesRead` (line 1000) `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)` - *! reads from the specified anonymous pipe and sends the result back to the teamserver @param AnonPipes @param RequestID*
- `PUTS` (line 1010) `PUTS( "Start reading anon pipe" )
    PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...`
- `PRINTF` (line 1023) `PRINTF( "dwRead => %d\n", dwRead )

        if ( dwRead == 0 )`
- `WinScreenshot` (line 1052) `BOOL WinScreenshot(
    OUT PVOID*  ImagePointer,
    OUT PSIZE_T ImageSize
)` - *! takes a BMP screenshot of the current desktop @param ImagePointer @param ImageSize @return*
- `PipeRead` (line 1175) `BOOL PipeRead(
    IN HANDLE  Handle,
    IN PBUFFER Buffer
)` - *! Read from the pipe and writes it to the specified buffer @param Handle handle to the pipe @param Buffer buffer to save the read bytes from the pi...*
- `PipeWrite` (line 1202) `BOOL PipeWrite(
    IN  HANDLE   Handle,
    OUT PBUFFER Buffer
)` - *! Write the specified buffer to the specified pipe @param Handle handle to the pipe @param Buffer buffer to write @return pipe write successful or not*
- `CfgQueryEnforced` (line 1227) `BOOL CfgQueryEnforced(
    VOID
)` - *! @brief check if CFG is enforced in this current process.  @return*
- `CfgAddressAdd` (line 1259) `VOID CfgAddressAdd(
    IN PVOID ImageBase,
    IN PVOID Function
)` - *! @brief add module + function to CFG exception list.  @param ImageBase @param Function*
- `EventSet` (line 1293) `BOOL EventSet(
    IN HANDLE Event
)` - *! Sets an event @param Event*
- `RandomNumber32` (line 1304) `ULONG RandomNumber32(
    VOID
)` - *! generates a random unsigned 32-bit integer @return*
- `RandomBool` (line 1321) `BOOL RandomBool(
    VOID
)` - *! generates a random bool @return*
- `SharedTimestamp` (line 1337) `ULONG64 SharedTimestamp(
    VOID
)` - *! get current timestamp since unix epoch from KUSER_SHARED_DATA @return*
- `SharedSleep` (line 1357) `VOID SharedSleep(
    ULONG64 Delay
)` - *! Sleep using KUSER_SHARED_DATA.SystemTime @param Delay*
- `ShuffleArray` (line 1378) `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)`
- `___chkstk_ms` (line 1395) `VOID volatile ___chkstk_ms(
        VOID
)`
- `DemonPrintf` (line 1401) `VOID DemonPrintf( PCHAR fmt, ... )` - *if defined(SEND_LOGS) && defined(DEBUG)*
- `LogToConsole` (line 1433) `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)` - *elif defined(SHELLCODE) && defined(DEBUG)*
- `listDir` (line 1477) `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...` - *endif*

#### `AesCrypt.c`
**Path:** `payloads/Demon/src/crypt/AesCrypt.c`

**Functions:**
- `KeyExpansion` (line 46) `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)` - *define getSBoxValue(num) (sbox[(num)])*
- `AesInit` (line 102) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)`
- `AddRoundKey` (line 111) `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)` - *This function adds the round key to state. The round key is added to the state by an XOR function.*
- `SubBytes` (line 125) `static void SubBytes(state_t* state)` - *The SubBytes Function Substitutes the values in the state matrix with values in an S-box.*
- `ShiftRows` (line 140) `static void ShiftRows(state_t* state)` - *The ShiftRows() function shifts the rows in the state to the left. Each row is shifted with different offset. Offset = Row number. So the first row...*
- `xtime` (line 167) `static UINT8 xtime(UINT8 x)`
- `MixColumns` (line 174) `static void MixColumns(state_t* state)` - *MixColumns function mixes the columns of the state matrix*
- `AesXCryptBuffer` (line 216) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)` - *if defined(CTR) && (CTR == 1)*

**Macros:**
- `Nb` (line 3)
- `Nk` (line 7)
- `Nr` (line 8)
- `Nk` (line 10)
- `Nr` (line 11)
- `Nk` (line 13)
- `Nr` (line 14)
- `MULTIPLY_AS_A_FUNCTION` (line 18)
- `getSBoxValue` (line 44)

#### `Inject.c`
**Path:** `payloads/Demon/src/inject/Inject.c`

**Functions:**
- `Inject` (line 27) `DWORD Inject(
    IN BYTE   Method,
    IN HANDLE Handle,
    IN DWORD  Pid,
    IN BOOL   x64,
 ...` - *Inject code into a remote process  @param Method    thread execution method. @param Handle    opened handle to the remote process. @param Pid      ...*
- `PRINTF` (line 64) `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )
    }

    /* check the archit...`
- `PRINTF` (line 91) `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )
    }

    /* write pay...`
- `PRINTF` (line 99) `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )
    }

    /* change a...`
- `PUTS` (line 107) `PUTS( "[INJECT] Changed memory protection from RW to RX" )
    }

    /* check if any args has be...`
- `PRINTF` (line 118) `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )
        }

    ...`
- `PRINTF` (line 126) `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )
        }
    }

    ...`
- `PRINTF` (line 135) `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )
    }

END:
    PUTS( ...`
- `DllInjectReflective` (line 171) `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...`
- `PRINTF` (line 232) `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )
    if ( ParamSize > 0 )` - *Alloc and write remote params*
- `PRINTF` (line 278) `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )

                if ( ! ThreadCreate( THREAD_MET...`
- `DllSpawnReflective` (line 321) `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...`

#### `InjectUtil.c`
**Path:** `payloads/Demon/src/inject/InjectUtil.c`

**Functions:**
- `Rva2Offset` (line 11) `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )` - *endif*
- `GetReflectiveLoaderOffset` (line 35) `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )`
- `GetPeArch` (line 71) `DWORD GetPeArch( PVOID PeBytes )`

#### `MainDll.c`
**Path:** `payloads/Demon/src/main/MainDll.c`

**Functions:**
- `Start` (line 8) `DLLEXPORT VOID Start(  )` - *Export this for rundll32 or any other program that requires and exported functions... * TODO: make this function name optional/changeable in the pa...*
- `DllMain` (line 24) `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...` - */* prevent exiting if started using rundll32 or something PVOID Kernel32  = LdrModulePeb( H_MODULE_KERNEL32 ); VOID ( WINAPI *DoSleep ) ( DWORD ) =...*

#### `MainExe.c`
**Path:** `payloads/Demon/src/main/MainExe.c`

**Functions:**
- `WinMain` (line 2) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` - *include <Demon.h>*

#### `MainSvc.c`
**Path:** `payloads/Demon/src/main/MainSvc.c`

**Functions:**
- `WinMain` (line 16) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` - */* Service handle and status variable SERVICE_STATUS_HANDLE StatusHandle = { 0 }; SERVICE_STATUS        SvcStatus    = { .dwServiceType      = SERV...*
- `SvcMain` (line 31) `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )` - *{ PRINTF( "WinMain (Service Main): hInstance:[%p]\n", hInstance ) SERVICE_TABLE_ENTRY DispatchTable[ ] = { { SERVICE_NAME, SvcMain }, { NULL, NULL ...*
- `SrvCtrlHandler` (line 40) `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`

#### `Entry.c`
**Path:** `payloads/DllLdr/Source/Entry.c`

**Functions:**
- `KaynLoader` (line 4) `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )` - *include <Core.h> include <Native.h> include <ntdef.h>*
- `KaynCaller` (line 143) `NAKED LPVOID KaynCaller( PVOID StartAddress )`
- `Memcpy` (line 165) `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )`
- `KGetModuleByHash` (line 184) `PVOID KGetModuleByHash( DWORD ModuleHash )`
- `CopyDotStr` (line 205) `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )`
- `KGetProcAddressByHash` (line 214) `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...`
- `KResolveIAT` (line 264) `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )`
- `KReAllocSections` (line 305) `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )`
- `KLoadLibrary` (line 330) `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )`
- `KHashString` (line 363) `DWORD KHashString( PVOID String, SIZE_T Length )` - *-------------------------------- ---- String & Data functions ---- ---------------------------------*
- `KStringLengthA` (line 392) `SIZE_T KStringLengthA( LPCSTR String )`
- `KStringLengthW` (line 399) `SIZE_T KStringLengthW(LPCWSTR String)`
- `KCharStringToWCharString` (line 408) `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`

#### `Hasher.c`
**Path:** `payloads/Shellcode/Scripts/Hasher.c`

**Functions:**
- `Hash` (line 3) `long Hash( char* String )` - *include <stdio.h> include <ctype.h>*
- `ToUpperString` (line 14) `void ToUpperString(char * temp)`
- `main` (line 23) `int main(int argc, char** argv)`

#### `Entry.c`
**Path:** `payloads/Shellcode/Source/Entry.c`

**Functions:**
- `SEC` (line 10) `SEC( text, B ) VOID Entry( VOID )` - *ifdef _WIN64 define IMAGE_REL_TYPE IMAGE_REL_BASED_DIR64 else define IMAGE_REL_TYPE IMAGE_REL_BASED_HIGHLOW endif*
- `KaynLdrReloc` (line 103) `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`

**Macros:**
- `IMAGE_REL_TYPE` (line 6)
- `IMAGE_REL_TYPE` (line 8)

#### `Utils.c`
**Path:** `payloads/Shellcode/Source/Utils.c`

**Functions:**
- `SEC` (line 3) `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )` - *include <Utils.h> include <Macro.h>*

#### `Win32.c`
**Path:** `payloads/Shellcode/Source/Win32.c`

**Functions:**
- `SEC` (line 4) `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )` - *include <Win32.h> include <Utils.h> include <winternl.h>*
- `SEC` (line 22) `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`

### CC (42 files)

#### `Connector.cc`
**Path:** `client/src/Havoc/Connector.cc`

**Functions:**
- `Connector` (line 6) `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )` - *include <Havoc/Connector.hpp> include <Havoc/Havoc.hpp> include <QCryptographicHash> include <QMap> include <QBuffer>*
- `connect` (line 18) `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )`
- `connect` (line 35) `QObject::connect( Socket, &QWebSocket::connected, this, [&]()`
- `connect` (line 43) `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()`
- `Disconnect` (line 55) `bool Connector::Disconnect()`
- `SendLogin` (line 71) `void Connector::SendLogin()`
- `SendPackage` (line 92) `void Connector::SendPackage( Util::Packager::PPackage Package )`

#### `DBManager.cc`
**Path:** `client/src/Havoc/DBManger/DBManager.cc`

**Functions:**
- `DBManager` (line 8) `DBManager::DBManager( const QString& FilePath, int OpenFlag )`
- `createNewDatabase` (line 31) `bool DBManager::createNewDatabase()`

#### `Scripts.cc`
**Path:** `client/src/Havoc/DBManger/Scripts.cc`

**Functions:**
- `AddScript` (line 2) `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )` - *include <Havoc/DBManager/DBManager.hpp>*
- `RemoveScript` (line 19) `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )`
- `CheckScript` (line 40) `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )`
- `GetScripts` (line 62) `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()`

#### `Teamserver.cc`
**Path:** `client/src/Havoc/DBManger/Teamserver.cc`

**Functions:**
- `addTeamserverInfo` (line 5) `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )`
- `checkTeamserverExists` (line 30) `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )`
- `removeTeamserverInfo` (line 54) `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )`
- `listTeamservers` (line 74) `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()`
- `removeAllTeamservers` (line 103) `bool HavocSpace::DBManager::removeAllTeamservers()`

#### `CommandOutput.cc`
**Path:** `client/src/Havoc/Demon/CommandOutput.cc`

**Functions:**
- `MessageOutput` (line 14) `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`

#### `CommandSend.cc`
**Path:** `client/src/Havoc/Demon/CommandSend.cc`

*No symbols extracted*

#### `Commands.cc`
**Path:** `client/src/Havoc/Demon/Commands.cc`

**Macros:**
- `BEHAVIOR_PROCESS_INJECTION` (line 2)
- `BEHAVIOR_PROCESS_CREATION` (line 4)
- `BEHAVIOR_FORK_AND_RUN` (line 5)
- `BEHAVIOR_API_ONLY` (line 6)
- `BEHAVIOR_TEAMSERVER` (line 7)
- `NO_SUBCOMMANDS` (line 8)

#### `ConsoleInput.cc`
**Path:** `client/src/Havoc/Demon/ConsoleInput.cc`

**Functions:**
- `is_number` (line 27) `static bool is_number( const std::string& s )`
- `compareQString` (line 182) `bool compareQString(const QString &a, const QString &b)`
- `DemonCommands` (line 187) `DemonCommands::DemonCommands( )`
- `SEND` (line 611) `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...`
- `SEND` (line 653) `SEND( Execute.Job( TaskID, "list", "0" ) )
            }
            else if ( InputCommands[ 1 ]...`
- `CONSOLE_ERROR` (line 667) `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- `CONSOLE_ERROR` (line 681) `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- `CONSOLE_ERROR` (line 700) `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )
            }
        }
        e...`
- `SEND` (line 1137) `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...`
- `SEND` (line 1165) `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...`
- `CONSOLE_ERROR` (line 1225) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- `CONSOLE_ERROR` (line 1260) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- `SEND` (line 1451) `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...`
- `SEND` (line 1458) `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...`
- `SEND` (line 1606) `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...`
- `SEND` (line 1619) `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...`
- `SEND` (line 1626) `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...`
- `SEND` (line 1653) `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...`
- `SEND` (line 1660) `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...`
- `SEND` (line 1673) `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...`
- `SEND` (line 1680) `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...`
- `SEND` (line 1697) `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...`
- `SEND` (line 1710) `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...`
- `SEND` (line 1723) `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...`
- `SEND` (line 1736) `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...`
- `CONSOLE_ERROR` (line 1830) `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...`
- `SEND` (line 2036) `SEND( Execute.Screenshot( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "net...`
- `CONSOLE_ERROR` (line 2131) `CONSOLE_ERROR( "No sub command specified" )
            }
        }
        else if ( InputComman...`
- `SEND` (line 2184) `SEND( Execute.Pivot( TaskID, Command, Param ) )
            }
        }
        else if ( InputCo...`
- `SEND` (line 2191) `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...`
- `SEND` (line 2323) `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...`

#### `Havoc.cc`
**Path:** `client/src/Havoc/Havoc.cc`

**Functions:**
- `Havoc` (line 6) `HavocSpace::Havoc::Havoc( QMainWindow* w )` - *include <QTimer>*
- `Init` (line 21) `void HavocSpace::Havoc::Init( int argc, char** argv )`
- `singleShot` (line 70) `QTimer::singleShot( 10, [&]()`
- `Start` (line 84) `void HavocSpace::Havoc::Start()`
- `Exit` (line 92) `void HavocSpace::Havoc::Exit()`

#### `Packager.cc`
**Path:** `client/src/Havoc/Packager.cc`

**Functions:**
- `DecodePackage` (line 62) `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )`
- `foreach` (line 90) `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )`
- `EncodePackage` (line 105) `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )`
- `DispatchInitConnection` (line 165) `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )`
- `DispatchListener` (line 219) `bool Packager::DispatchListener( Util::Packager::PPackage Package )`
- `DispatchChat` (line 482) `bool Packager::DispatchChat( Util::Packager::PPackage Package)`
- `DispatchGate` (line 531) `bool Packager::DispatchGate( Util::Packager::PPackage Package )`
- `DispatchSession` (line 580) `bool Packager::DispatchSession( Util::Packager::PPackage Package )`
- `case` (line 720) `case ( int ) Commands::CONSOLE_MESSAGE:

                            if ( QByteArray::fromBase64(...`
- `case` (line 734) `case ( int ) Commands::BOF_CALLBACK:

                            if ( QByteArray::fromBase64( Ou...`
- `DispatchService` (line 864) `bool Packager::DispatchService( Util::Packager::PPackage Package )`
- `DispatchTeamserver` (line 960) `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
- `setTeamserver` (line 985) `void Packager::setTeamserver( QString Name )`

#### `Event.cc`
**Path:** `client/src/Havoc/PythonApi/Event.cc`

**Functions:**
- `EventClass_dealloc` (line 69) `void EventClass_dealloc( PPyEvents self )`
- `EventClass_new` (line 76) `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `EventClass_init` (line 85) `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds )`
- `EventClass_OnNewSession` (line 95) `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args )` - *Methods*
- `EventClass_OnDemonOutput` (line 111) `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args )`

**Macros:**
- `AllocMov` (line 61)

#### `Havoc.cc`
**Path:** `client/src/Havoc/PythonApi/Havoc.cc`

**Functions:**
- `PyInit_Havoc` (line 44) `PyMODINIT_FUNC PythonAPI::Havoc::PyInit_Havoc( void )`
- `Load` (line 66) `PyObject* PythonAPI::Havoc::Core::Load( PyObject *self, PyObject *args )`
- `GetListeners` (line 88) `PyObject* PythonAPI::Havoc::Core::GetListeners( PyObject *self, PyObject *args )`
- `GetAgents` (line 104) `PyObject* PythonAPI::Havoc::Core::GetAgents( PyObject *self, PyObject *args )`
- `GetDemons` (line 122) `PyObject* PythonAPI::Havoc::Core::GetDemons( PyObject *self, PyObject *args )`
- `GeneratePayload` (line 138) `PyObject* PythonAPI::Havoc::Core::GeneratePayload( PyObject *self, PyObject *args, PyObject* kwar...`
- `RegisterCommand` (line 188) `PyObject* PythonAPI::Havoc::Core::RegisterCommand( PyObject *self, PyObject *args, PyObject* kwar...` - *RegisterCommand( PyFunction: func, Module: str, Command: str, Description: str, Behavior: int, Usage: str, Example: str )*
- `RegisterModule` (line 265) `PyObject* PythonAPI::Havoc::Core::RegisterModule( PyObject *self, PyObject *args )` - *RegisterModule( Name: str, Description: str, Behavior: str, Usage: str, Example: str, Options: str )*
- `RegisterCallback` (line 320) `PyObject* PythonAPI::Havoc::Core::RegisterCallback( PyObject *self, PyObject *args )`

#### `HavocUi.cc`
**Path:** `client/src/Havoc/PythonApi/HavocUi.cc`

**Functions:**
- `CreateTab` (line 45) `PyObject* PythonAPI::HavocUI::Core::CreateTab(PyObject *self, PyObject *args)`
- `connect` (line 76) `QMainWindow::connect( tupleCallback, &QAction::triggered, HavocX::HavocUserInterface->HavocWindow...`
- `MessageBox` (line 82) `PyObject* PythonAPI::HavocUI::Core::MessageBox(PyObject *self, PyObject *args)`
- `ErrorMessage` (line 107) `PyObject* PythonAPI::HavocUI::Core::ErrorMessage(PyObject *self, PyObject *args)`
- `QuestionDialog` (line 122) `PyObject* PythonAPI::HavocUI::Core::QuestionDialog(PyObject *self, PyObject *args)`
- `InputDialog` (line 140) `PyObject* PythonAPI::HavocUI::Core::InputDialog(PyObject *self, PyObject *args)`
- `OpenFileDialog` (line 153) `PyObject* PythonAPI::HavocUI::Core::OpenFileDialog(PyObject *self, PyObject *args)`
- `SaveFileDialog` (line 166) `PyObject* PythonAPI::HavocUI::Core::SaveFileDialog(PyObject *self, PyObject *args)`
- `ColorDialog` (line 179) `PyObject* PythonAPI::HavocUI::Core::ColorDialog(PyObject *self, PyObject *args)`
- `ProgressDialog` (line 191) `PyObject* PythonAPI::HavocUI::Core::ProgressDialog(PyObject *self, PyObject *args)`
- `connect` (line 211) `QMainWindow::connect( timer, &QTimer::timeout, HavocX::HavocUserInterface->HavocWindow, [callable...`
- `connect` (line 231) `QMainWindow::connect( cancelButton, &QPushButton::clicked, HavocX::HavocUserInterface->HavocWindo...`
- `PyInit_HavocUI` (line 240) `PyMODINIT_FUNC PythonAPI::HavocUI::PyInit_HavocUI(void)`

#### `PyAgentClass.cc`
**Path:** `client/src/Havoc/PythonApi/PyAgentClass.cc`

**Functions:**
- `AgentClass_dealloc` (line 68) `void AgentClass_dealloc( PPyAgentClass self )`
- `AgentClass_new` (line 75) `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `AgentClass_init` (line 84) `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds )`
- `AgentClass_ConsoleWrite` (line 111) `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args )`
- `AgentClass_Command` (line 148) `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args )`

**Macros:**
- `PY_SSIZE_T_CLEAN` (line 1)

#### `PyDemonClass.cc`
**Path:** `client/src/Havoc/PythonApi/PyDemonClass.cc`

**Functions:**
- `DemonClass_dealloc` (line 99) `void DemonClass_dealloc( PPyDemonClass self )`
- `DemonClass_new` (line 118) `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `DemonClass_init` (line 127) `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds )`
- `DemonClass_Shell` (line 179) `PyObject* DemonClass_Shell( PPyDemonClass self, PyObject *args )` - *Demon.shell( TaskID: str, ShellCommands: str )*
- `DemonClass_InlineExecute` (line 200) `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args )` - *Demon.InlineExecute( TaskID: str, EntryFunc: str, Path: str, Args: str, Threaded: bool )*
- `DemonClass_InlineExecuteGetOutput` (line 249) `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args )`
- `DemonClass_DotnetInlineExecute` (line 312) `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args )` - *Demon.DotnetInlineExecute( TaskID: str, Path: str, Args: str )*
- `DemonClass_Command` (line 332) `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args )`
- `DemonClass_CommandGetOutput` (line 352) `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args )`
- `DemonClass_ShellcodeSpawn` (line 389) `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args )` - *ShellcodeSpawn( QString TaskID, QString InjectionTechnique, QString TargetArch, QString Path, QString Arguments )*
- `DemonClass_DllInject` (line 430) `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args )` - *Demon.DllInject( TaskID: str, Pid: str, DllPath: str, DllArgs: str )*
- `DemonClass_DllSpawn` (line 453) `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args )` - *Demon.DllInject( TaskID: str, DllPath: str, DllArgs: str )*
- `DemonClass_ProcessCreate` (line 491) `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args )` - *Demon.ProcessCreate( TaskID: str App: str, Cmdline: str, Suspended: bool, Piped: bool, Verbose: bool )*
- `DemonClass_ConsoleWrite` (line 539) `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args )` - *Other Methods*

**Macros:**
- `PY_SSIZE_T_CLEAN` (line 1)
- `AllocMov` (line 91)

#### `PythonApi.cc`
**Path:** `client/src/Havoc/PythonApi/PythonApi.cc`

**Functions:**
- `Stdout_write` (line 5) `PyObject* Stdout_write(PyObject* self, PyObject* args)`
- `Stdout_flush` (line 21) `PyObject* Stdout_flush(PyObject* self, PyObject* args)`
- `PyInit_emb` (line 86) `PyMODINIT_FUNC PyInit_emb(void)`
- `set_stdout` (line 104) `void set_stdout(stdout_write_type write)`
- `reset_stdout` (line 117) `void reset_stdout()`

#### `PyDialogClass.cc`
**Path:** `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

**Functions:**
- `DialogClass_dealloc` (line 85) `void DialogClass_dealloc( PPyDialogClass self )`
- `DialogClass_new` (line 98) `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `DialogClass_init` (line 120) `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds )`
- `DialogClass_exec` (line 155) `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args )` - *Methods*
- `DialogClass_addLabel` (line 162) `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args )`
- `DialogClass_addImage` (line 176) `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args )`
- `DialogClass_addButton` (line 192) `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args )`
- `connect` (line 212) `QObject::connect(button, &QPushButton::clicked, self->DialogWindow->window, [button_callback]()`
- `DialogClass_addCheckbox` (line 218) `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args )`
- `connect` (line 241) `QObject::connect(checkbox, &QCheckBox::clicked, self->DialogWindow->window, [checkbox_callback]()`
- `DialogClass_addCombobox` (line 247) `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args )`
- `connect` (line 265) `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- `DialogClass_addLineedit` (line 271) `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args )`
- `connect` (line 289) `QObject::connect(line, &QLineEdit::editingFinished, self->DialogWindow->window, [line, line_callb...`
- `DialogClass_addCalendar` (line 299) `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args )`
- `connect` (line 316) `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->DialogWindow->window, [cal, cal_c...`
- `DialogClass_addDial` (line 328) `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args )`
- `connect` (line 345) `QObject::connect(dial, &QDial::valueChanged, self->DialogWindow->window, [cal_callback](long value)`
- `DialogClass_addSlider` (line 351) `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args )`
- `connect` (line 374) `QObject::connect(slider, &QSlider::valueChanged, self->DialogWindow->window, [cal_callback](long ...`
- `DialogClass_replaceLabel` (line 380) `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args )`
- `DialogClass_close` (line 404) `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args )`
- `DialogClass_clear` (line 411) `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args )`

**Macros:**
- `PY_SSIZE_T_CLEAN` (line 1)
- `AllocMov` (line 77)

#### `PyLoggerClass.cc`
**Path:** `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

**Functions:**
- `LoggerClass_dealloc` (line 76) `void LoggerClass_dealloc( PPyLoggerClass self )`
- `LoggerClass_new` (line 85) `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `LoggerClass_init` (line 94) `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds )`
- `LoggerClass_setBottomTab` (line 122) `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args )` - *Methods*
- `LoggerClass_setSmallTab` (line 129) `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args )`
- `LoggerClass_addText` (line 136) `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args )`
- `LoggerClass_clear` (line 148) `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args )`

**Macros:**
- `PY_SSIZE_T_CLEAN` (line 1)
- `AllocMov` (line 68)

#### `PyTreeClass.cc`
**Path:** `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

**Functions:**
- `TreeClass_dealloc` (line 77) `void TreeClass_dealloc( PPyTreeClass self )`
- `TreeClass_new` (line 90) `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `TreeClass_init` (line 111) `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds )`
- `connect` (line 164) `QObject::connect(self->TreeWindow->tree_view->selectionModel(), &QItemSelectionModel::selectionCh...`
- `TreeClass_setBottomTab` (line 180) `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args )` - *Methods*
- `TreeClass_setSmallTab` (line 187) `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args )`
- `TreeClass_addRow` (line 194) `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args )`
- `TreeClass_setItem` (line 217) `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args )`
- `TreeClass_setPanel` (line 232) `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args )`

**Macros:**
- `PY_SSIZE_T_CLEAN` (line 1)
- `AllocMov` (line 69)

#### `PyWidgetClass.cc`
**Path:** `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

**Functions:**
- `WidgetClass_dealloc` (line 85) `void WidgetClass_dealloc( PPyWidgetClass self )`
- `WidgetClass_new` (line 98) `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `WidgetClass_init` (line 118) `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds )`
- `WidgetClass_addLabel` (line 149) `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args )` - *Methods*
- `WidgetClass_addImage` (line 162) `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_setBottomTab` (line 178) `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_setSmallTab` (line 185) `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_addButton` (line 192) `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args )`
- `connect` (line 212) `QObject::connect(button, &QPushButton::clicked, self->WidgetWindow->window, [button_callback]()`
- `WidgetClass_addCheckbox` (line 218) `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args )`
- `connect` (line 241) `QObject::connect(checkbox, &QCheckBox::clicked, self->WidgetWindow->window, [checkbox_callback]()`
- `WidgetClass_addCombobox` (line 247) `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args )`
- `connect` (line 265) `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- `WidgetClass_addLineedit` (line 271) `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args )`
- `connect` (line 289) `QObject::connect(line, &QLineEdit::editingFinished, self->WidgetWindow->window, [line, line_callb...`
- `WidgetClass_addCalendar` (line 299) `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args )`
- `connect` (line 316) `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->WidgetWindow->window, [cal, cal_c...`
- `WidgetClass_addDial` (line 328) `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args )`
- `connect` (line 345) `QObject::connect(dial, &QDial::valueChanged, self->WidgetWindow->window, [cal_callback](long value)`
- `WidgetClass_addSlider` (line 351) `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args )`
- `connect` (line 374) `QObject::connect(slider, &QSlider::valueChanged, self->WidgetWindow->window, [cal_callback](long ...`
- `WidgetClass_replaceLabel` (line 380) `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_clear` (line 404) `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args )`

**Macros:**
- `PY_SSIZE_T_CLEAN` (line 1)
- `AllocMov` (line 77)

#### `Service.cc`
**Path:** `client/src/Havoc/Service.cc`

*No symbols extracted*

#### `Main.cc`
**Path:** `client/src/Main.cc`

*No symbols extracted*

#### `About.cc`
**Path:** `client/src/UserInterface/Dialogs/About.cc`

**Functions:**
- `About` (line 3) `About::About( QDialog* dialog )` - *include <global.hpp> include <UserInterface/Dialogs/About.hpp>*
- `setupUi` (line 48) `void About::setupUi()`
- `onButtonClose` (line 53) `void About::onButtonClose()`

#### `Connect.cc`
**Path:** `client/src/UserInterface/Dialogs/Connect.cc`

**Functions:**
- `setupUi` (line 8) `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )` - *include <UserInterface/Dialogs/Connect.hpp>*
- `connect` (line 141) `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()`
- `connect` (line 145) `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()`
- `connect` (line 149) `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()`
- `connect` (line 153) `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()`
- `connect` (line 157) `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()`
- `StartDialog` (line 164) `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )`
- `passDB` (line 228) `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...`
- `onButton_Connect` (line 233) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()`
- `itemSelected` (line 317) `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()`
- `onButton_NewProfile` (line 339) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()`
- `handleContextMenu` (line 355) `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )`
- `itemRemove` (line 361) `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()`
- `itemsClear` (line 375) `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()`

#### `Listener.cc`
**Path:** `client/src/UserInterface/Dialogs/Listener.cc`

**Functions:**
- `is_number` (line 16) `bool is_number( const std::string& s )`
- `NewListener` (line 23) `NewListener::NewListener( QDialog* Dialog )`
- `connect` (line 331) `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()`
- `connect` (line 338) `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()`
- `connect` (line 355) `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()`
- `connect` (line 365) `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()`
- `connect` (line 376) `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()`
- `connect` (line 386) `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()`
- `connect` (line 397) `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()`
- `connect` (line 407) `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- `Start` (line 449) `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )`
- `onButton_Save` (line 816) `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()`
- `onProxyEnabled` (line 946) `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()`

#### `Payload.cc`
**Path:** `client/src/UserInterface/Dialogs/Payload.cc`

**Functions:**
- `setupUi` (line 16) `void Payload::setupUi( QDialog* Dialog )`
- `connect` (line 124) `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- `buttonGenerate` (line 189) `void Payload::buttonGenerate()`

#### `HavocUi.cc`
**Path:** `client/src/UserInterface/HavocUi.cc`

**Functions:**
- `setupUi` (line 27) `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)`
- `OneSecondTick` (line 199) `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()`
- `MarkSessionAs` (line 204) `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...`
- `UpdateSessionsHealth` (line 261) `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()`
- `retranslateUi` (line 360) `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const`
- `ConnectEvents` (line 394) `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()`
- `connect` (line 398) `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()`
- `connect` (line 403) `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()`
- `connect` (line 407) `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()`
- `connect` (line 421) `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()`
- `connect` (line 430) `QMainWindow::connect( actionExit, &QAction::triggered, this, []()`
- `connect` (line 434) `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()`
- `connect` (line 438) `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()`
- `connect` (line 454) `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()`
- `connect` (line 466) `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()`
- `connect` (line 478) `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()`
- `connect` (line 482) `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()`
- `connect` (line 497) `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()`
- `connect` (line 505) `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()`
- `connect` (line 515) `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()`
- `connect` (line 529) `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()`
- `connect` (line 548) `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()`
- `connect` (line 557) `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()`
- `connect` (line 561) `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()`
- `NewBottomTab` (line 566) `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...`
- `setDBManager` (line 571) `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)`
- `NewTeamserverTab` (line 576) `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )`
- `NewTeamserverTab` (line 586) `void UserInterface::HavocUi::NewTeamserverTab(QString Name )`
- `NewSmallTab` (line 595) `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const`
- `PythonPrepare` (line 601) `void UserInterface::HavocUi::PythonPrepare()`

#### `EventViewer.cc`
**Path:** `client/src/UserInterface/SmallWidgets/EventViewer.cc`

**Functions:**
- `setupUi` (line 3) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)` - *include <UserInterface/SmallWidgets/EventViewer.hpp> include <Util/ColorText.h>*
- `AppendText` (line 22) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`

#### `Chat.cc`
**Path:** `client/src/UserInterface/Widgets/Chat.cc`

**Functions:**
- `setupUi` (line 10) `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )` - *include <Havoc/Packager.hpp> include <Havoc/Connector.hpp>*
- `AppendText` (line 62) `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...`
- `AddUserMessage` (line 69) `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...`
- `AppendFromInput` (line 77) `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()`

#### `DemonInteracted.cc`
**Path:** `client/src/UserInterface/Widgets/DemonInteracted.cc`

**Functions:**
- `DemonInput` (line 15) `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )`
- `handleKeyPress` (line 20) `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )`
- `handleTabKey` (line 38) `void DemonInteracted::DemonInput::handleTabKey()`
- `handleUpKey` (line 46) `void DemonInteracted::DemonInput::handleUpKey()`
- `handleDownKey` (line 66) `void DemonInteracted::DemonInput::handleDownKey()`
- `event` (line 77) `bool DemonInteracted::DemonInput::event( QEvent* e )`
- `AddCommand` (line 89) `void DemonInteracted::DemonInput::AddCommand( const QString &Command )`
- `setupUi` (line 94) `void DemonInteracted::setupUi( QWidget *Form )`
- `AppendFromInput` (line 208) `void DemonInteracted::AppendFromInput()`
- `AppendText` (line 213) `void DemonInteracted::AppendText( const QString& text )`
- `TaskInfo` (line 280) `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const`
- `TaskError` (line 295) `QString DemonInteracted::TaskError( const QString &text ) const`
- `AppendRaw` (line 302) `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)`
- `AppendNoNL` (line 307) `void DemonInteracted::AppendNoNL( const QString &text )`
- `AutoCompleteAdd` (line 316) `void DemonInteracted::AutoCompleteAdd( QString text )`
- `AutoCompleteClear` (line 325) `void DemonInteracted::AutoCompleteClear()`
- `AutoCompleteAddList` (line 335) `void DemonInteracted::AutoCompleteAddList( QStringList list )`

#### `FileBrowser.cc`
**Path:** `client/src/UserInterface/Widgets/FileBrowser.cc`

**Functions:**
- `setupUi` (line 39) `void FileBrowser::setupUi( QWidget* FileBrowser )`
- `retranslateUi` (line 147) `void FileBrowser::retranslateUi()`
- `AddData` (line 158) `void FileBrowser::AddData( QJsonDocument JsonData )`
- `TreeAddData` (line 233) `void FileBrowser::TreeAddData( FileData Data )`
- `TableAddData` (line 238) `void FileBrowser::TableAddData( FileData Data )`
- `onTableDoubleClick` (line 275) `void FileBrowser::onTableDoubleClick( int row, int column )`
- `onTreeDoubleClick` (line 290) `void FileBrowser::onTreeDoubleClick()`
- `ChangePathAndSendRequest` (line 296) `void FileBrowser::ChangePathAndSendRequest( QString Path )`
- `TableClear` (line 312) `void FileBrowser::TableClear()`
- `onButtonUp` (line 319) `void FileBrowser::onButtonUp()`
- `onTableMenuDownload` (line 327) `void FileBrowser::onTableMenuDownload()`
- `onTableContextMenu` (line 361) `void FileBrowser::onTableContextMenu( const QPoint &pos )`
- `onTreeContextMenu` (line 370) `void FileBrowser::onTreeContextMenu( const QPoint &pos )`
- `onTableMenuMkdir` (line 378) `void FileBrowser::onTableMenuMkdir()`
- `onTableMenuReload` (line 383) `void FileBrowser::onTableMenuReload()`
- `onTableMenuRemove` (line 404) `void FileBrowser::onTableMenuRemove()`
- `onTreeMenuListDrives` (line 409) `void FileBrowser::onTreeMenuListDrives()`
- `onTreeMenuMkdir` (line 414) `void FileBrowser::onTreeMenuMkdir()`
- `onTreeMenuReload` (line 419) `void FileBrowser::onTreeMenuReload()`
- `onTreeMenuRemove` (line 424) `void FileBrowser::onTreeMenuRemove()`
- `onInputPath` (line 429) `void FileBrowser::onInputPath()`
- `TreeUpdate` (line 437) `void FileBrowser::TreeUpdate()`
- `TreeClear` (line 499) `void FileBrowser::TreeClear( )`
- `TreeAddDisk` (line 522) `void FileBrowser::TreeAddDisk( QString Disk )`
- `TreeAddChildToParent` (line 536) `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )`

#### `ListenersTable.cc`
**Path:** `client/src/UserInterface/Widgets/ListenersTable.cc`

**Functions:**
- `setupUi` (line 14) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )` - *include <QMap>*
- `ButtonsInit` (line 84) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()`
- `connect` (line 87) `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()`
- `connect` (line 107) `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()`
- `connect` (line 151) `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()`
- `ListenerAdd` (line 177) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...`
- `setDBManager` (line 283) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...`
- `CreateNewPackage` (line 288) `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...`
- `ListenerEdit` (line 311) `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const`
- `ListenerRemove` (line 322) `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const`
- `ListenerError` (line 356) `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...`

#### `LootWidget.cc`
**Path:** `client/src/UserInterface/Widgets/LootWidget.cc`

**Functions:**
- `ImageLabel` (line 17) `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )` - *imagelabel.cpp*
- `resizeEvent` (line 32) `void ImageLabel::resizeEvent( QResizeEvent* event )`
- `pixmap` (line 38) `const QPixmap* ImageLabel::pixmap() const`
- `event` (line 43) `bool ImageLabel::event( QEvent* e )`
- `keyReleaseEvent` (line 59) `void ImageLabel::keyReleaseEvent( QKeyEvent* event )`
- `wheelEvent` (line 70) `void ImageLabel::wheelEvent( QWheelEvent* ev )`
- `setPixmap` (line 77) `void ImageLabel::setPixmap( const QPixmap &pixmap )`
- `resizeImage` (line 84) `void ImageLabel::resizeImage()`
- `LootWidget` (line 91) `LootWidget::LootWidget()`
- `AddScreenshot` (line 252) `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...`
- `AddDownload` (line 272) `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...`
- `Reload` (line 291) `void LootWidget::Reload()`
- `onScreenshotTableClick` (line 304) `void LootWidget::onScreenshotTableClick( const QModelIndex &index )`
- `onDownloadTableClick` (line 328) `void LootWidget::onDownloadTableClick( const QModelIndex &index )`
- `onAgentChange` (line 333) `void LootWidget::onAgentChange( const QString& text )`
- `AddSessionSection` (line 363) `void LootWidget::AddSessionSection( const QString& AgentID )`
- `onShowChange` (line 376) `void LootWidget::onShowChange( const QString& text )`
- `ScreenshotTableAdd` (line 388) `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )`
- `DownloadTableAdd` (line 413) `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )`
- `onScreenshotTableCtx` (line 435) `void LootWidget::onScreenshotTableCtx( const QPoint &pos )`

#### `ProcessList.cc`
**Path:** `client/src/UserInterface/Widgets/ProcessList.cc`

**Functions:**
- `setupUi` (line 4) `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)` - *include <UserInterface/Widgets/ProcessList.hpp> include <UserInterface/Widgets/DemonInteracted.h> include <QClipboard>*
- `UpdateProcessListJson` (line 200) `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...`
- `NewTableProcess` (line 230) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...`
- `NewTreeProcess` (line 278) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...`
- `onButton_Refresh` (line 298) `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const`
- `onTableChange` (line 313) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()`
- `onTreeChange` (line 329) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()`
- `handleTableListMenuContext` (line 342) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...`
- `handleTreeListMenuContext` (line 350) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...`
- `onActionCopyPID` (line 358) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()`
- `onActionSetParentProcess` (line 366) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()`

#### `PythonScript.cc`
**Path:** `client/src/UserInterface/Widgets/PythonScript.cc`

**Functions:**
- `setupUi` (line 7) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)` - *include <UserInterface/Widgets/PythonScript.hpp> include <Util/ColorText.h> include <QThread> include <thread> include <QTime> include <Havoc/Pytho...*
- `RunCode` (line 47) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )`
- `AppendFromInput` (line 63) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()`
- `AppendOutput` (line 75) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )`

#### `ScriptManager.cc`
**Path:** `client/src/UserInterface/Widgets/ScriptManager.cc`

**Functions:**
- `SetupUi` (line 12) `void ScriptManager::SetupUi( QWidget *Form )`
- `RetranslateUi` (line 103) `void ScriptManager::RetranslateUi( )`
- `AddScript` (line 110) `bool ScriptManager::AddScript( QString Path )`
- `AddScriptTable` (line 139) `void ScriptManager::AddScriptTable( QString Path )`
- `b_LoadScript` (line 153) `void ScriptManager::b_LoadScript()`
- `menu_ScriptMenu` (line 185) `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const`
- `ReloadScript` (line 194) `void ScriptManager::ReloadScript() const`
- `RemoveScript` (line 204) `void ScriptManager::RemoveScript() const` - *TODO: clear python interpreter and reload every script except the one that got removed*

#### `SessionGraph.cc`
**Path:** `client/src/UserInterface/Widgets/SessionGraph.cc`

**Functions:**
- `GraphWidget` (line 27) `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )`
- `GraphNodeAdd` (line 53) `Node* GraphWidget::GraphNodeAdd( SessionItem Session )`
- `GraphNodeRemove` (line 83) `void GraphWidget::GraphNodeRemove( SessionItem Session )`
- `GraphPivotNodeAdd` (line 104) `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )`
- `GraphPivotNodeDisconnect` (line 146) `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )`
- `GraphPivotNodeReconnect` (line 169) `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )`
- `itemMoved` (line 197) `void GraphWidget::itemMoved()`
- `keyPressEvent` (line 203) `void GraphWidget::keyPressEvent( QKeyEvent* event )`
- `timerEvent` (line 220) `void GraphWidget::timerEvent( QTimerEvent* event )`
- `resizeEvent` (line 250) `void GraphWidget::resizeEvent( QResizeEvent* event )`
- `wheelEvent` (line 257) `void GraphWidget::wheelEvent( QWheelEvent* event )`
- `drawBackground` (line 262) `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )`
- `scaleView` (line 278) `void GraphWidget::scaleView( qreal scaleFactor )`
- `shuffle` (line 287) `void GraphWidget::shuffle()`
- `zoomIn` (line 298) `void GraphWidget::zoomIn()`
- `zoomOut` (line 303) `void GraphWidget::zoomOut()`
- `GraphNodeGet` (line 308) `Node *GraphWidget::GraphNodeGet( QString AgentID )`
- `initNode` (line 329) `void GraphWidget::initNode(Node* v)` - *Initialize node properties for layout*
- `layout` (line 340) `void GraphWidget::layout(Node* T)` - *Entry function for layout*
- `firstWalk` (line 350) `void GraphWidget::firstWalk(Node* v)` - *Calculate preliminary x-coordinates for all nodes*
- `apportion` (line 383) `void GraphWidget::apportion(Node* v, Node*& defaultAncestor)` - *Adjusts spacing between subtrees to ensure they don't overlap*
- `moveSubtree` (line 434) `void GraphWidget::moveSubtree(Node* wm, Node* wp, double shift)` - *Move the subtree rooted at wp so it's shifted away from the subtree rooted at wm*
- `nextLeft` (line 453) `Node* GraphWidget::nextLeft(Node* v)` - *Helper function to get the leftmost child or thread (left contour)*
- `nextRight` (line 462) `Node* GraphWidget::nextRight(Node* v)` - *Helper function to get the rightmost child or thread (right contour)*
- `ancestor` (line 471) `Node* GraphWidget::ancestor(Node* vim, Node* v, Node*& defaultAncestor)` - *Get the ancestor of vim that is in the same subtree as v, or return defaultAncestor*
- `executeShifts` (line 481) `void GraphWidget::executeShifts(Node* v)` - *Propagate the shifts down to ensure subtrees are moved accordingly*
- `secondWalk` (line 496) `void GraphWidget::secondWalk(Node* v, double m, double depth)` - *Walk the tree again to assign final x and y coordinates to each node*
- `Edge` (line 508) `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )
    : source( sourceNode ), dest( de...` - *================================================== =================== Edge Class =================== =============================================...*
- `sourceNode` (line 518) `Node* Edge::sourceNode() const`
- `destNode` (line 523) `Node* Edge::destNode() const`
- `contextMenuEvent` (line 528) `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )`
- `adjust` (line 797) `void Edge::adjust()`
- `boundingRect` (line 821) `QRectF Edge::boundingRect() const`
- `paint` (line 834) `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )`
- `Color` (line 862) `void Edge::Color( QColor color )`
- `Node` (line 871) `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...` - *================================================== =================== Node Class =================== =============================================...*
- `appendChild` (line 886) `void Node::appendChild( Node* child )`
- `removeChild` (line 891) `void Node::removeChild( Node* child )`
- `boundingRect` (line 898) `QRectF Node::boundingRect() const`
- `addEdge` (line 903) `void Node::addEdge( Edge* edge )`
- `edges` (line 909) `QVector<Edge*> Node::edges() const`
- `calculateForces` (line 914) `void Node::calculateForces()`
- `mouseMoveEvent` (line 935) `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )`
- `advancePosition` (line 940) `bool Node::advancePosition()`
- `shape` (line 949) `QPainterPath Node::shape() const`
- `paint` (line 958) `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )`
- `itemChange` (line 1006) `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )`
- `mousePressEvent` (line 1025) `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )`
- `mouseReleaseEvent` (line 1031) `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )`

#### `SessionTable.cc`
**Path:** `client/src/UserInterface/Widgets/SessionTable.cc`

**Functions:**
- `setupUi` (line 15) `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...`
- `NewSessionItem` (line 81) `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...`
- `ChangeSessionValue` (line 210) `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...`
- `updateRow` (line 219) `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()`

#### `Store.cc`
**Path:** `client/src/UserInterface/Widgets/Store.cc`

**Functions:**
- `setupUi` (line 9) `void Store::setupUi( QWidget* Store)` - *include <QScrollBar>*
- `connect` (line 75) `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()`
- `connect` (line 108) `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()`
- `connect` (line 115) `QObject::connect(installButton, &QPushButton::clicked, [this]()`
- `displayData` (line 133) `void Store::displayData(int position)`
- `AddScript` (line 146) `bool Store::AddScript( QString Path )`
- `installScript` (line 175) `void Store::installScript(int position)`
- `retranslateUi` (line 223) `void Store::retranslateUi()`

#### `Teamserver.cc`
**Path:** `client/src/UserInterface/Widgets/Teamserver.cc`

**Functions:**
- `setupUi` (line 4) `void Teamserver::setupUi( QWidget* Teamserver )` - *include <QScrollBar>*
- `retranslateUi` (line 25) `void Teamserver::retranslateUi()`
- `AddLoggerText` (line 30) `void Teamserver::AddLoggerText( const QString& Text ) const`

#### `TeamserverTabSession.cc`
**Path:** `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

**Functions:**
- `setupUi` (line 26) `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...`
- `connect` (line 121) `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )`
- `connect` (line 140) `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...`
- `handleDemonContextMenu` (line 164) `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )`
- `NewBottomTab` (line 467) `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...`
- `NewWidgetTab` (line 487) `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...`
- `removeTabSmall` (line 508) `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const`

#### `global.cc`
**Path:** `client/src/global.cc`

**Functions:**
- `gen_random` (line 30) `std::string Util::gen_random( const int len )`
- `Export` (line 41) `void Util::SessionItem::Export()`

### CPP (3 files)

#### `Base.cpp`
**Path:** `client/src/Util/Base.cpp`

*No symbols extracted*

#### `Base64.cpp`
**Path:** `client/src/Util/Base64.cpp`

**Functions:**
- `base64_encode` (line 8) `std::string HavocNamespace::Util::base64_encode(const char* buf, unsigned int bufLen)`

#### `ColorText.cpp`
**Path:** `client/src/Util/ColorText.cpp`

**Functions:**
- `SetDraculaDark` (line 23) `void HavocNamespace::Util::ColorText::SetDraculaDark()`
- `SetDraculaLight` (line 39) `void HavocNamespace::Util::ColorText::SetDraculaLight()`
- `Color` (line 44) `QString HavocNamespace::Util::ColorText::Color(const QString& color, const QString &text)`
- `Background` (line 49) `QString HavocNamespace::Util::ColorText::Background(const QString& text)`
- `Foreground` (line 54) `QString HavocNamespace::Util::ColorText::Foreground(const QString& text)`
- `Comment` (line 58) `QString HavocNamespace::Util::ColorText::Comment(const QString& text)`
- `Cyan` (line 62) `QString HavocNamespace::Util::ColorText::Cyan(const QString& text)`
- `Green` (line 66) `QString HavocNamespace::Util::ColorText::Green(const QString& text)`
- `Orange` (line 70) `QString HavocNamespace::Util::ColorText::Orange(const QString& text)`
- `Pink` (line 74) `QString HavocNamespace::Util::ColorText::Pink(const QString& text)`
- `Purple` (line 78) `QString HavocNamespace::Util::ColorText::Purple(const QString& text)`
- `Red` (line 82) `QString HavocNamespace::Util::ColorText::Red(const QString& text)`
- `Yellow` (line 86) `QString HavocNamespace::Util::ColorText::Yellow(const QString& text)`
- `Bold` (line 90) `QString HavocNamespace::Util::ColorText::Bold(const QString& text)`
- `Underline` (line 94) `QString HavocNamespace::Util::ColorText::Underline(const QString &text)`
- `UnderlineBackground` (line 98) `QString HavocNamespace::Util::ColorText::UnderlineBackground(const QString &text)`
- `UnderlineForeground` (line 102) `QString HavocNamespace::Util::ColorText::UnderlineForeground(const QString &text)`
- `UnderlineComment` (line 106) `QString HavocNamespace::Util::ColorText::UnderlineComment(const QString &text)`
- `UnderlineCyan` (line 110) `QString HavocNamespace::Util::ColorText::UnderlineCyan(const QString &text)`
- `UnderlineGreen` (line 114) `QString HavocNamespace::Util::ColorText::UnderlineGreen(const QString &text)`
- `UnderlineOrange` (line 118) `QString HavocNamespace::Util::ColorText::UnderlineOrange(const QString &text)`
- `UnderlinePink` (line 122) `QString HavocNamespace::Util::ColorText::UnderlinePink(const QString &text)`
- `UnderlinePurple` (line 126) `QString HavocNamespace::Util::ColorText::UnderlinePurple(const QString &text)`
- `UnderlineRed` (line 130) `QString HavocNamespace::Util::ColorText::UnderlineRed(const QString &text)`
- `UnderlineYellow` (line 134) `QString HavocNamespace::Util::ColorText::UnderlineYellow(const QString &text)`

### GO (202 files)

#### `client.go`
**Path:** `teamserver/cmd/client.go`

*No symbols extracted*

#### `cmd.go`
**Path:** `teamserver/cmd/cmd.go`

**Functions:**
- `init` (line 29) `func init(` - *init all flags*
- `teamserverFunc` (line 47) `func teamserverFunc(`
- `startMenu` (line 61) `func startMenu(`

#### `agent.go`
**Path:** `teamserver/cmd/server/agent.go`

**Functions:**
- `AgentUpdate` (line 16) `func (t *Teamserver) AgentUpdate(`
- `Died` (line 23) `func (t *Teamserver) Died(`
- `UnlinkFromAll` (line 30) `func (t *Teamserver) UnlinkFromAll(`
- `ParentOf` (line 53) `func (t *Teamserver) ParentOf(`
- `LinksOf` (line 60) `func (t *Teamserver) LinksOf(`
- `LinkAdd` (line 66) `func (t *Teamserver) LinkAdd(`
- `LinkRemove` (line 78) `func (t *Teamserver) LinkRemove(`
- `AgentHasDied` (line 102) `func (t *Teamserver) AgentHasDied(`
- `AgentAdd` (line 108) `func (t *Teamserver) AgentAdd(`
- `AgentSendNotify` (line 123) `func (t *Teamserver) AgentSendNotify(`
- `AgentCallbackSize` (line 138) `func (t *Teamserver) AgentCallbackSize(`
- `AgentInstance` (line 155) `func (t *Teamserver) AgentInstance(`
- `AgentLastTimeCalled` (line 166) `func (t *Teamserver) AgentLastTimeCalled(`
- `AgentExist` (line 183) `func (t *Teamserver) AgentExist(`
- `AgentConsole` (line 198) `func (t *Teamserver) AgentConsole(`
- `PythonModuleCallback` (line 208) `func (t *Teamserver) PythonModuleCallback(`
- `AgentCallback` (line 220) `func (t *Teamserver) AgentCallback(`
- `SendLogs` (line 233) `func (t *Teamserver) SendLogs(`
- `GetDotNetPipeTemplate` (line 237) `func (t *Teamserver) GetDotNetPipeTemplate(`

#### `dispatch.go`
**Path:** `teamserver/cmd/server/dispatch.go`

**Functions:**
- `DispatchEvent` (line 20) `func (t *Teamserver) DispatchEvent(`

#### `listener.go`
**Path:** `teamserver/cmd/server/listener.go`

**Functions:**
- `ListenerStart` (line 19) `func (t *Teamserver) ListenerStart(`
- `ListenerExist` (line 113) `func (t *Teamserver) ListenerExist(`
- `ListenerGetInfo` (line 124) `func (t *Teamserver) ListenerGetInfo(`
- `ListenerRemove` (line 144) `func (t *Teamserver) ListenerRemove(`
- `ListenerEdit` (line 192) `func (t *Teamserver) ListenerEdit(`
- `ListenerAdd` (line 220) `func (t *Teamserver) ListenerAdd(` - *ListenerAdd creates a package for the client that a new listener has been added.*
- `ListenerServiceExc2Add` (line 337) `func (t *Teamserver) ListenerServiceExc2Add(` - *ListenerServiceExc2Add adds an external c2 listener that has been started from a service script to the teamserver listener list.*
- `ListenerStartNotify` (line 378) `func (t *Teamserver) ListenerStartNotify(` - *ListenerStartNotify Notifies the clients of a new listener that is available to use.*

#### `service.go`
**Path:** `teamserver/cmd/server/service.go`

**Functions:**
- `ServiceAgent` (line 9) `func (t *Teamserver) ServiceAgent(`
- `ServiceAgentExist` (line 20) `func (t *Teamserver) ServiceAgentExist(`

#### `teamserver.go`
**Path:** `teamserver/cmd/server/teamserver.go`

**Functions:**
- `NewTeamserver` (line 37) `func NewTeamserver(`
- `SetServerFlags` (line 48) `func (t *Teamserver) SetServerFlags(`
- `Start` (line 52) `func (t *Teamserver) Start(`
- `handleRequest` (line 497) `func (t *Teamserver) handleRequest(`
- `SetProfile` (line 626) `func (t *Teamserver) SetProfile(`
- `ClientAuthenticate` (line 637) `func (t *Teamserver) ClientAuthenticate(`
- `EventBroadcast` (line 690) `func (t *Teamserver) EventBroadcast(`
- `EventNewDemon` (line 709) `func (t *Teamserver) EventNewDemon(`
- `EventAgentMark` (line 713) `func (t *Teamserver) EventAgentMark(`
- `EventListenerError` (line 720) `func (t *Teamserver) EventListenerError(`
- `SendEvent` (line 741) `func (t *Teamserver) SendEvent(`
- `RemoveClient` (line 773) `func (t *Teamserver) RemoveClient(`
- `EventAppend` (line 797) `func (t *Teamserver) EventAppend(`
- `EventRemove` (line 812) `func (t *Teamserver) EventRemove(`
- `SendAllPackagesToNewClient` (line 818) `func (t *Teamserver) SendAllPackagesToNewClient(`
- `FindSystemPackages` (line 842) `func (t *Teamserver) FindSystemPackages(`
- `EndpointAdd` (line 933) `func (t *Teamserver) EndpointAdd(`
- `EndpointRemove` (line 945) `func (t *Teamserver) EndpointRemove(`

#### `types.go`
**Path:** `teamserver/cmd/server/types.go`

**Structs:**
- `Listener` (line 16)
- `Client` (line 22)
- `Users` (line 34)
- `serverFlags` (line 41)
- `utilFlags` (line 53)
- `TeamserverFlags` (line 63)
- `Endpoint` (line 68)
- `Teamserver` (line 73)

#### `server.go`
**Path:** `teamserver/cmd/server.go`

*No symbols extracted*

#### `main.go`
**Path:** `teamserver/main.go`

**Functions:**
- `main` (line 6) `func main(`

#### `agent.go`
**Path:** `teamserver/pkg/agent/agent.go`

**Functions:**
- `BuildPayloadMessage` (line 29) `func BuildPayloadMessage(`
- `ParseHeader` (line 181) `func ParseHeader(`
- `RegisterInfoToInstance` (line 215) `func RegisterInfoToInstance(`
- `ParseDemonRegisterRequest` (line 328) `func ParseDemonRegisterRequest(`
- `IsKnownRequestID` (line 609) `func (a *Agent) IsKnownRequestID(` - *check that the request the agent is valid*
- `AddRequest` (line 632) `func (a *Agent) AddRequest(` - *the operator added a new request/command*
- `RequestCompleted` (line 638) `func (a *Agent) RequestCompleted(` - *after a request has been completed, we can forget about the RequestID so that it is no longer valid*
- `AddJobToQueue` (line 647) `func (a *Agent) AddJobToQueue(`
- `GetQueuedJobs` (line 661) `func (a *Agent) GetQueuedJobs(`
- `UpdateLastCallback` (line 739) `func (a *Agent) UpdateLastCallback(`
- `PivotAddJob` (line 746) `func (a *Agent) PivotAddJob(`
- `DownloadAdd` (line 816) `func (a *Agent) DownloadAdd(`
- `DownloadWrite` (line 865) `func (a *Agent) DownloadWrite(`
- `DownloadClose` (line 888) `func (a *Agent) DownloadClose(`
- `DownloadGet` (line 902) `func (a *Agent) DownloadGet(`
- `PortFwdNew` (line 911) `func (a *Agent) PortFwdNew(`
- `PortFwdGet` (line 929) `func (a *Agent) PortFwdGet(`
- `PortFwdIsOpen` (line 948) `func (a *Agent) PortFwdIsOpen(`
- `PortFwdOpen` (line 958) `func (a *Agent) PortFwdOpen(`
- `PortFwdWrite` (line 979) `func (a *Agent) PortFwdWrite(`
- `PortFwdRead` (line 997) `func (a *Agent) PortFwdRead(`
- `PortFwdClose` (line 1023) `func (a *Agent) PortFwdClose(`
- `SocksClientAdd` (line 1053) `func (a *Agent) SocksClientAdd(`
- `SocksClientGet` (line 1073) `func (a *Agent) SocksClientGet(`
- `SocksClientRead` (line 1096) `func (a *Agent) SocksClientRead(`
- `SocksClientClose` (line 1130) `func (a *Agent) SocksClientClose(`
- `SocksServerRemove` (line 1163) `func (a *Agent) SocksServerRemove(`
- `ToMap` (line 1193) `func (a *Agent) ToMap(` - *ToMap returns the agent info as a map*
- `ToJson` (line 1224) `func (a *Agent) ToJson(`
- `AgentsAppend` (line 1238) `func (agents *Agents) AgentsAppend(`
- `getWindowsVersionString` (line 1243) `func getWindowsVersionString(`

#### `commands.go`
**Path:** `teamserver/pkg/agent/commands.go`

*No symbols extracted*

#### `demons.go`
**Path:** `teamserver/pkg/agent/demons.go`

**Functions:**
- `UploadMemFileInChunks` (line 31) `func (a *Agent) UploadMemFileInChunks(` - *we upload heavy files to the implant in chunks, so SMB agents can handle the size*
- `TeamserverTaskPrepare` (line 64) `func (a *Agent) TeamserverTaskPrepare(`
- `TaskPrepare` (line 128) `func (a *Agent) TaskPrepare(`
- `TaskDispatch` (line 2285) `func (a *Agent) TaskDispatch(`
- `Console` (line 6430) `func (a *Agent) Console(`

#### `types.go`
**Path:** `teamserver/pkg/agent/types.go`

**Interfaces:**
- `DemonInterface` (line 19)
- `EventInterface` (line 23)
- `ServiceAgentInterface` (line 33)
- `TeamServer` (line 40) - *TeamServer interface that allows us to interact with the core teamserver*

**Structs:**
- `Header` (line 26)
- `Job` (line 73)
- `Pivots` (line 89)
- `Download` (line 94)
- `BofCallback` (line 104)
- `PortFwd` (line 111)
- `SocksClient` (line 124)
- `SocksServer` (line 133)
- `Agent` (line 139) - *TODO: maybe change this to type map[string]any instead of struct*
- `AgentInfo` (line 174)
- `Agents` (line 212)

#### `colors.go`
**Path:** `teamserver/pkg/colors/colors.go`

*No symbols extracted*

#### `builder.go`
**Path:** `teamserver/pkg/common/builder/builder.go`

**Functions:**
- `NewBuilder` (line 141) `func NewBuilder(`
- `SetSilent` (line 213) `func (b *Builder) SetSilent(`
- `Build` (line 217) `func (b *Builder) Build(`
- `SetListener` (line 459) `func (b *Builder) SetListener(`
- `SetPatchConfig` (line 464) `func (b *Builder) SetPatchConfig(`
- `SetFormat` (line 481) `func (b *Builder) SetFormat(`
- `SetArch` (line 485) `func (b *Builder) SetArch(`
- `SetConfig` (line 489) `func (b *Builder) SetConfig(`
- `SetOutputPath` (line 501) `func (b *Builder) SetOutputPath(`
- `SetExtension` (line 505) `func (b *Builder) SetExtension(`
- `GetOutputPath` (line 509) `func (b *Builder) GetOutputPath(`
- `Patch` (line 513) `func (b *Builder) Patch(`
- `PatchConfig` (line 561) `func (b *Builder) PatchConfig(`
- `GetPayloadBytes` (line 1024) `func (b *Builder) GetPayloadBytes(`
- `Cmd` (line 1064) `func (b *Builder) Cmd(`
- `CompileCmd` (line 1090) `func (b *Builder) CompileCmd(`
- `GetListenerDefines` (line 1102) `func (b *Builder) GetListenerDefines(`
- `DeletePayload` (line 1122) `func (b *Builder) DeletePayload(`

**Structs:**
- `BuilderConfig` (line 70)
- `Builder` (line 78)

#### `https.go`
**Path:** `teamserver/pkg/common/certs/https.go`

**Functions:**
- `randomState` (line 115) `func randomState(`
- `randomLocality` (line 123) `func randomLocality(`
- `randomStreetAddress` (line 132) `func randomStreetAddress(`
- `randomProvinceLocalityStreetAddress` (line 137) `func randomProvinceLocalityStreetAddress(`
- `randomPostalCode` (line 144) `func randomPostalCode(`
- `randomSubject` (line 153) `func randomSubject(`
- `randomOrganization` (line 166) `func randomOrganization(`
- `publicKey` (line 182) `func publicKey(`
- `randomInt` (line 193) `func randomInt(`
- `pemBlockForKey` (line 200) `func pemBlockForKey(`
- `generateCertificate` (line 216) `func generateCertificate(`
- `HTTPSGenerateRSACertificate` (line 300) `func HTTPSGenerateRSACertificate(` - *HTTPSGenerateRSACertificate - Generate a server certificate signed with a given CA*

#### `aes.go`
**Path:** `teamserver/pkg/common/crypt/aes.go`

**Functions:**
- `XCryptBytesAES256` (line 10) `func XCryptBytesAES256(`

#### `packer.go`
**Path:** `teamserver/pkg/common/packer/packer.go`

**Functions:**
- `NewPacker` (line 22) `func NewPacker(`
- `AddInt64` (line 29) `func (p *Packer) AddInt64(`
- `AddInt32` (line 37) `func (p *Packer) AddInt32(`
- `AddInt` (line 45) `func (p *Packer) AddInt(`
- `AddUInt32` (line 54) `func (p *Packer) AddUInt32(` - *AddUInt32 use a much as possible this function*
- `AddString` (line 62) `func (p *Packer) AddString(`
- `AddWString` (line 66) `func (p *Packer) AddWString(`
- `AddBytes` (line 70) `func (p *Packer) AddBytes(`
- `Build` (line 80) `func (p *Packer) Build(`
- `Buffer` (line 95) `func (p *Packer) Buffer(`
- `Size` (line 99) `func (p *Packer) Size(`
- `AddOwnSizeFirst` (line 103) `func (p *Packer) AddOwnSizeFirst(`

**Structs:**
- `Packer` (line 14)

#### `parser.go`
**Path:** `teamserver/pkg/common/parser/parser.go`

**Functions:**
- `NewParser` (line 24) `func NewParser(`
- `CanIRead` (line 31) `func (p *Parser) CanIRead(`
- `ParseInt32` (line 82) `func (p *Parser) ParseInt32(`
- `ParseInt64` (line 106) `func (p *Parser) ParseInt64(`
- `ParseBool` (line 130) `func (p *Parser) ParseBool(`
- `ParsePointer` (line 154) `func (p *Parser) ParsePointer(`
- `SetBigEndian` (line 158) `func (p *Parser) SetBigEndian(`
- `ParseBytes` (line 162) `func (p *Parser) ParseBytes(`
- `ParseAtLeastBytes` (line 177) `func (p *Parser) ParseAtLeastBytes(`
- `ParseUTF16String` (line 189) `func (p *Parser) ParseUTF16String(`
- `ParseString` (line 193) `func (p *Parser) ParseString(`
- `Length` (line 197) `func (p *Parser) Length(`
- `Buffer` (line 201) `func (p *Parser) Buffer(`
- `DecryptBuffer` (line 205) `func (p *Parser) DecryptBuffer(`

**Structs:**
- `Parser` (line 19)

#### `util.go`
**Path:** `teamserver/pkg/common/util.go`

**Functions:**
- `ParseWorkingHours` (line 26) `func ParseWorkingHours(`
- `Bmp2Png` (line 76) `func Bmp2Png(`
- `DecodeUTF16` (line 99) `func DecodeUTF16(`
- `EncodeUTF16` (line 118) `func EncodeUTF16(`
- `EncodeUTF8` (line 135) `func EncodeUTF8(`
- `ByteCountSI` (line 144) `func ByteCountSI(`
- `XorCipher` (line 158) `func XorCipher(`
- `RandomString` (line 166) `func RandomString(`
- `Int32ToLittle` (line 175) `func Int32ToLittle(`
- `StripNull` (line 181) `func StripNull(`
- `PercentageChange` (line 185) `func PercentageChange(`
- `IpStringToInt32` (line 189) `func IpStringToInt32(`
- `Int32ToIpString` (line 198) `func Int32ToIpString(`
- `EpochTimeToSystemTime` (line 209) `func EpochTimeToSystemTime(`
- `GetRandomChar` (line 222) `func GetRandomChar(`
- `GeneratePipeName` (line 227) `func GeneratePipeName(` - *generate a PipeName from a name template*
- `GetInterfaceIpv4Addr` (line 279) `func GetInterfaceIpv4Addr(`

#### `agents.go`
**Path:** `teamserver/pkg/db/agents.go`

**Functions:**
- `AgentAdd` (line 12) `func (db *DB) AgentAdd(`
- `AgentUpdate` (line 81) `func (db *DB) AgentUpdate(`
- `AgentHasDied` (line 145) `func (db *DB) AgentHasDied(`
- `AgentExist` (line 163) `func (db *DB) AgentExist(`
- `AgentRemove` (line 192) `func (db *DB) AgentRemove(`
- `AgentAll` (line 211) `func (db *DB) AgentAll(`

#### `db.go`
**Path:** `teamserver/pkg/db/db.go`

**Functions:**
- `DatabaseNew` (line 16) `func DatabaseNew(`
- `init` (line 48) `func (db *DB) init(`
- `Existed` (line 69) `func (db *DB) Existed(`
- `Path` (line 73) `func (db *DB) Path(`

**Structs:**
- `DB` (line 10)

#### `links.go`
**Path:** `teamserver/pkg/db/links.go`

**Functions:**
- `LinkAdd` (line 8) `func (db *DB) LinkAdd(`
- `LinkExist` (line 46) `func (db *DB) LinkExist(`
- `ParentOf` (line 75) `func (db *DB) ParentOf(`
- `LinksOf` (line 104) `func (db *DB) LinksOf(`
- `LinkRemove` (line 136) `func (db *DB) LinkRemove(`

#### `listeners.go`
**Path:** `teamserver/pkg/db/listeners.go`

**Functions:**
- `ListenerAdd` (line 8) `func (db *DB) ListenerAdd(`
- `ListenerExist` (line 46) `func (db *DB) ListenerExist(`
- `ListenerAll` (line 66) `func (db *DB) ListenerAll(`
- `ListenerCount` (line 107) `func (db *DB) ListenerCount(`
- `ListenerNames` (line 126) `func (db *DB) ListenerNames(`
- `ListenerRemove` (line 152) `func (db *DB) ListenerRemove(`

#### `misc.go`
**Path:** `teamserver/pkg/db/misc.go`

*No symbols extracted*

#### `chatlog.go`
**Path:** `teamserver/pkg/events/chatlog.go`

**Functions:**
- `NewUserConnected` (line 11) `func (chatLog) NewUserConnected(`
- `UserDisconnected` (line 27) `func (chatLog) UserDisconnected(`

#### `demons.go`
**Path:** `teamserver/pkg/events/demons.go`

**Functions:**
- `NewDemon` (line 19) `func (demons) NewDemon(`
- `DemonOutput` (line 83) `func (demons) DemonOutput(`
- `CallBack` (line 105) `func (demons) CallBack(`
- `MarkAs` (line 121) `func (demons) MarkAs(`

#### `events.go`
**Path:** `teamserver/pkg/events/events.go`

**Functions:**
- `Authenticated` (line 22) `func Authenticated(`
- `UserAlreadyExits` (line 56) `func UserAlreadyExits(`
- `UserDoNotExists` (line 72) `func UserDoNotExists(`
- `SendProfile` (line 88) `func SendProfile(`

#### `gate.go`
**Path:** `teamserver/pkg/events/gate.go`

**Functions:**
- `SendStageless` (line 12) `func (g gate) SendStageless(`
- `SendConsoleMessage` (line 30) `func (g gate) SendConsoleMessage(`

#### `listeners.go`
**Path:** `teamserver/pkg/events/listeners.go`

**Functions:**
- `ListenerAdd` (line 15) `func (listeners) ListenerAdd(`
- `ListenerEdit` (line 97) `func (listeners) ListenerEdit(`
- `ListenerError` (line 154) `func (listeners) ListenerError(`
- `ListenerRemove` (line 173) `func (listeners) ListenerRemove(`
- `ListenerMark` (line 187) `func (listeners) ListenerMark(`

#### `service.go`
**Path:** `teamserver/pkg/events/service.go`

**Functions:**
- `AgentRegister` (line 11) `func (service) AgentRegister(`
- `ListenerRegister` (line 25) `func (service) ListenerRegister(`

#### `teamserver.go`
**Path:** `teamserver/pkg/events/teamserver.go`

**Functions:**
- `Logger` (line 11) `func (teamserver) Logger(`
- `Profile` (line 25) `func (teamserver) Profile(`

#### `external.go`
**Path:** `teamserver/pkg/handlers/external.go`

**Functions:**
- `NewExternal` (line 15) `func NewExternal(`
- `Start` (line 24) `func (e *External) Start(`
- `Request` (line 37) `func (e *External) Request(` - *Request The way the external c2 handles or parses the request is like the HTTP listener. Only one agent package can be parsed (at least for the dem...*

#### `handlers.go`
**Path:** `teamserver/pkg/handlers/handlers.go`

**Functions:**
- `parseAgentRequest` (line 23) `func parseAgentRequest(` - *parseAgentRequest parses the agent request and handles the given data. return 2 types. Response is the data/bytes once this function finished parsi...*
- `handleDemonAgent` (line 56) `func handleDemonAgent(` - *handleDemonAgent parse the demon agent request return 2 types:  Response bytes.Buffer Success  bool*
- `handleServiceAgent` (line 311) `func handleServiceAgent(` - *handleServiceAgent handles and parses a service agent request return 2 types:  Response bytes.Buffer Success  bool*
- `notifyTaskSize` (line 349) `func notifyTaskSize(` - *notifyTaskSize notifies every connected operator client how much we send to agent.*

#### `http.go`
**Path:** `teamserver/pkg/handlers/http.go`

**Functions:**
- `NewConfigHttp` (line 24) `func NewConfigHttp(`
- `generateCertFiles` (line 32) `func (h *HTTP) generateCertFiles(`
- `fake404` (line 80) `func (h *HTTP) fake404(` - *fake nginx 404 page*
- `request` (line 93) `func (h *HTTP) request(`
- `Start` (line 203) `func (h *HTTP) Start(`
- `Stop` (line 277) `func (h *HTTP) Stop(`

#### `smb.go`
**Path:** `teamserver/pkg/handlers/smb.go`

**Functions:**
- `NewPivotSmb` (line 8) `func NewPivotSmb(`
- `Start` (line 14) `func (s *SMB) Start(`

#### `types.go`
**Path:** `teamserver/pkg/handlers/types.go`

*No symbols extracted*

#### `global.go`
**Path:** `teamserver/pkg/logger/global.go`

**Functions:**
- `init` (line 11) `func init(`
- `NewLogger` (line 15) `func NewLogger(`
- `Info` (line 27) `func Info(`
- `Good` (line 31) `func Good(`
- `Debug` (line 35) `func Debug(`
- `DebugError` (line 39) `func DebugError(`
- `Warn` (line 43) `func Warn(`
- `Error` (line 47) `func Error(`
- `Fatal` (line 51) `func Fatal(`
- `Panic` (line 55) `func Panic(`
- `SetDebug` (line 59) `func SetDebug(`
- `ShowTime` (line 63) `func ShowTime(`
- `SetStdOut` (line 67) `func SetStdOut(`

#### `logger.go`
**Path:** `teamserver/pkg/logger/logger.go`

**Functions:**
- `FunctionTrace` (line 15) `func FunctionTrace(`
- `Info` (line 43) `func (logger *Logger) Info(`
- `Good` (line 52) `func (logger *Logger) Good(`
- `Debug` (line 61) `func (logger *Logger) Debug(`
- `DebugError` (line 74) `func (logger *Logger) DebugError(`
- `Warn` (line 87) `func (logger *Logger) Warn(`
- `Error` (line 96) `func (logger *Logger) Error(`
- `Fatal` (line 105) `func (logger *Logger) Fatal(`
- `Panic` (line 115) `func (logger *Logger) Panic(`
- `SetDebug` (line 125) `func (logger *Logger) SetDebug(`
- `ShowTime` (line 129) `func (logger *Logger) ShowTime(`

**Structs:**
- `Logger` (line 34)

#### `demon.go`
**Path:** `teamserver/pkg/logr/demon.go`

**Functions:**
- `AddAgentInput` (line 15) `func (l Logr) AddAgentInput(`
- `AddAgentRaw` (line 50) `func (l Logr) AddAgentRaw(`
- `DemonAddOutput` (line 82) `func (l Logr) DemonAddOutput(`
- `DemonAddDownloadedFile` (line 134) `func (l Logr) DemonAddDownloadedFile(`
- `DemonSaveScreenshot` (line 177) `func (l Logr) DemonSaveScreenshot(`

#### `listener.go`
**Path:** `teamserver/pkg/logr/listener.go`

**Functions:**
- `ListenerAddKeyCert` (line 3) `func (l Logr) ListenerAddKeyCert(`

#### `logr.go`
**Path:** `teamserver/pkg/logr/logr.go`

**Functions:**
- `NewLogr` (line 21) `func NewLogr(`

**Structs:**
- `Logr` (line 9)

#### `server.go`
**Path:** `teamserver/pkg/logr/server.go`

**Functions:**
- `strip` (line 12) `func strip(`
- `ServerStdOutInit` (line 21) `func (l Logr) ServerStdOutInit(`

#### `packages.go`
**Path:** `teamserver/pkg/packager/packages.go`

**Functions:**
- `NewPackager` (line 9) `func NewPackager(`
- `CreatePackage` (line 13) `func (p Packager) CreatePackage(`

#### `types.go`
**Path:** `teamserver/pkg/packager/types.go`

*No symbols extracted*

#### `config.go`
**Path:** `teamserver/pkg/profile/config.go`

**Structs:**
- `HavocConfig` (line 3)
- `WebHookDiscordConfig` (line 12)
- `WebHookConfig` (line 18)
- `BuildConfig` (line 22)
- `ServiceConfig` (line 28)
- `ServerProfile` (line 33)
- `OperatorsBlock` (line 42)
- `UsersBlock` (line 46)
- `Listeners` (line 51)
- `ListenerHTTP` (line 57)
- `ListenerSMB` (line 87)
- `ListenerExternal` (line 97)
- `ListenerHttpResponse` (line 102)
- `ListenerHttpProxy` (line 106)
- `ListenerHttpCerts` (line 113)
- `HeaderBlock` (line 118)
- `Binary` (line 127)
- `ProcessInjectionBlock` (line 134)
- `Demon` (line 139)

#### `profile.go`
**Path:** `teamserver/pkg/profile/profile.go`

**Functions:**
- `NewProfile` (line 13) `func NewProfile(`
- `SetProfile` (line 17) `func (p *Profile) SetProfile(`
- `ServerHost` (line 32) `func (p *Profile) ServerHost(`
- `ServerPort` (line 39) `func (p *Profile) ServerPort(`
- `ListOfUsernames` (line 46) `func (p *Profile) ListOfUsernames(`

**Structs:**
- `Profile` (line 9)

#### `diagnostic.go`
**Path:** `teamserver/pkg/profile/yaotl/diagnostic.go`

**Functions:**
- `Error` (line 76) `func (d *Diagnostic) Error(` - *error implementation, so that diagnostics can be returned via APIs that normally deal in vanilla Go errors.  This presents only minimal context abo...*
- `Error` (line 82) `func (d Diagnostics) Error(` - *error implementation, so that sets of diagnostics can be returned via APIs that normally deal in vanilla Go errors.*
- `Append` (line 104) `func (d Diagnostics) Append(` - *Append appends a new error to a Diagnostics and return the whole Diagnostics.  This is provided as a convenience for returning from a function that...*
- `Extend` (line 113) `func (d Diagnostics) Extend(` - *Extend concatenates the given Diagnostics with the receiver and returns the whole new Diagnostics.  This is similar to Append but accepts multiple ...*
- `HasErrors` (line 119) `func (d Diagnostics) HasErrors(` - *HasErrors returns true if the receiver contains any diagnostics of severity DiagError.*
- `Errs` (line 128) `func (d Diagnostics) Errs(`

**Interfaces:**
- `DiagnosticWriter` (line 140) - *A DiagnosticWriter emits diagnostics somehow.*

**Structs:**
- `Diagnostic` (line 26) - *Diagnostic represents information to be presented to a user about an error or anomaly in parsing or evaluating configuration.*

#### `diagnostic_text.go`
**Path:** `teamserver/pkg/profile/yaotl/diagnostic_text.go`

**Functions:**
- `NewDiagnosticTextWriter` (line 34) `func NewDiagnosticTextWriter(` - *NewDiagnosticTextWriter creates a DiagnosticWriter that writes diagnostics to the given writer as formatted text.  It is designed to produce text a...*
- `WriteDiagnostic` (line 43) `func (w *diagnosticTextWriter) WriteDiagnostic(`
- `WriteDiagnostics` (line 208) `func (w *diagnosticTextWriter) WriteDiagnostics(`
- `traversalStr` (line 218) `func (w *diagnosticTextWriter) traversalStr(`
- `valueStr` (line 246) `func (w *diagnosticTextWriter) valueStr(`
- `contextString` (line 302) `func contextString(`

**Structs:**
- `diagnosticTextWriter` (line 15)

#### `didyoumean.go`
**Path:** `teamserver/pkg/profile/yaotl/didyoumean.go`

**Functions:**
- `nameSuggestion` (line 16) `func nameSuggestion(` - *nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns it if found. If no suggesti...*

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/doc.go`

*No symbols extracted*

#### `eval_context.go`
**Path:** `teamserver/pkg/profile/yaotl/eval_context.go`

**Functions:**
- `NewChild` (line 17) `func (ctx *EvalContext) NewChild(` - *NewChild returns a new EvalContext that is a child of the receiver.*
- `Parent` (line 23) `func (ctx *EvalContext) Parent(` - *Parent returns the parent of the receiver, or nil if the receiver has no parent.*

**Structs:**
- `EvalContext` (line 10) - *An EvalContext provides the variables and functions that should be used to evaluate an expression.*

#### `expr_call.go`
**Path:** `teamserver/pkg/profile/yaotl/expr_call.go`

**Functions:**
- `ExprCall` (line 14) `func ExprCall(` - *ExprCall tests if the given expression is a function call and, if so, extracts the function name and the expressions that represent the arguments. ...*

**Structs:**
- `StaticCall` (line 41) - *StaticCall represents a function call that was extracted statically from an expression using ExprCall.*

#### `expr_list.go`
**Path:** `teamserver/pkg/profile/yaotl/expr_list.go`

**Functions:**
- `ExprList` (line 14) `func ExprList(` - *ExprList tests if the given expression is a static list construct and, if so, extracts the expressions that represent the list elements. If the giv...*

#### `expr_map.go`
**Path:** `teamserver/pkg/profile/yaotl/expr_map.go`

**Functions:**
- `ExprMap` (line 14) `func ExprMap(` - *ExprMap tests if the given expression is a static map construct and, if so, extracts the expressions that represent the map elements. If the given ...*

**Structs:**
- `KeyValuePair` (line 41) - *KeyValuePair represents a pair of expressions that serve as a single item within a map or object definition construct.*

#### `expr_unwrap.go`
**Path:** `teamserver/pkg/profile/yaotl/expr_unwrap.go`

**Functions:**
- `UnwrapExpression` (line 28) `func UnwrapExpression(` - *type-assert on the physical AST types used by the underlying syntax.  Unwrapping an expression may modify its behavior by stripping away any additi...*
- `UnwrapExpressionUntil` (line 54) `func UnwrapExpressionUntil(` - *UnwrapExpressionUntil is similar to UnwrapExpression except it gives the caller an opportunity to test each level of unwrapping to see each a parti...*

**Interfaces:**
- `unwrapExpression` (line 3)

#### `customdecode.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

**Functions:**
- `CustomExpressionDecoderForType` (line 48) `func CustomExpressionDecoderForType(` - *CustomExpressionDecoderForType takes any cty type and returns its custom expression decoder implementation if it has one. If it is not a capsule ty...*

#### `expression_type.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go`

**Functions:**
- `ExpressionVal` (line 27) `func ExpressionVal(` - *ExpressionVal returns a new cty value of type ExpressionType, wrapping the given expression.*
- `ExpressionFromVal` (line 33) `func ExpressionFromVal(` - *ExpressionFromVal returns the expression encapsulated in the given value, or panics if the value is not a known value of ExpressionType.*
- `ExpressionClosureVal` (line 58) `func ExpressionClosureVal(` - *ExpressionClosureVal returns a new cty value of type ExpressionClosureType, wrapping the given expression closure.*
- `Value` (line 64) `func (c *ExpressionClosure) Value(` - *Value evaluates the closure's expression using the closure's EvalContext, returning the result.*
- `ExpressionClosureFromVal` (line 75) `func ExpressionClosureFromVal(` - *ExpressionClosureFromVal returns the expression closure encapsulated in the given value, or panics if the value is not a known value of ExpressionC...*
- `init` (line 82) `func init(`

**Structs:**
- `ExpressionClosure` (line 51) - *ExpressionClosure is the type encapsulated in ExpressionClosureType*

#### `expand_body.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go`

**Functions:**
- `Content` (line 29) `func (b *expandBody) Content(`
- `PartialContent` (line 46) `func (b *expandBody) PartialContent(`
- `extendSchema` (line 85) `func (b *expandBody) extendSchema(`
- `prepareAttributes` (line 121) `func (b *expandBody) prepareAttributes(`
- `expandBlocks` (line 151) `func (b *expandBody) expandBlocks(`
- `expandChild` (line 232) `func (b *expandBody) expandChild(`
- `JustAttributes` (line 239) `func (b *expandBody) JustAttributes(`
- `MissingItemRange` (line 246) `func (b *expandBody) MissingItemRange(`

**Structs:**
- `expandBody` (line 12) - *expandBody wraps another hcl.Body and expands any "dynamic" blocks found inside whenever Content or PartialContent is called.*

#### `expand_body_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go`

**Functions:**
- `TestExpand` (line 13) `func TestExpand(`
- `TestExpandUnknownBodies` (line 336) `func TestExpandUnknownBodies(`

#### `expand_spec.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go`

**Functions:**
- `decodeSpec` (line 22) `func (b *expandBody) decodeSpec(`
- `newBlock` (line 153) `func (s *expandSpec) newBlock(`

**Structs:**
- `expandSpec` (line 11)

#### `expr_wrap.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go`

**Functions:**
- `Variables` (line 13) `func (e exprWrap) Variables(`
- `Value` (line 33) `func (e exprWrap) Value(`
- `UnwrapExpression` (line 40) `func (e exprWrap) UnwrapExpression(` - *UnwrapExpression returns the expression being wrapped by this instance. This allows the original expression to be recovered by hcl.UnwrapExpression.*

**Structs:**
- `exprWrap` (line 8)

#### `iteration.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go`

**Functions:**
- `MakeIteration` (line 15) `func (s *expandSpec) MakeIteration(`
- `Object` (line 24) `func (i *iteration) Object(`
- `EvalContext` (line 31) `func (i *iteration) EvalContext(`
- `MakeChild` (line 45) `func (i *iteration) MakeChild(`

**Structs:**
- `iteration` (line 8)

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/public.go`

**Functions:**
- `Expand` (line 42) `func Expand(` - *dynamic "child" { for_each = child_objs content { dynamic "grandchild" { for_each = child.value.children labels   = [grandchild.key] content { pare...*

#### `schema.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/schema.go`

*No symbols extracted*

#### `unknown_body.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go`

**Functions:**
- `Unknown` (line 24) `func (b unknownBody) Unknown(` - *hcldec.UnkownBody impl*
- `Content` (line 28) `func (b unknownBody) Content(`
- `PartialContent` (line 38) `func (b unknownBody) PartialContent(`
- `JustAttributes` (line 49) `func (b unknownBody) JustAttributes(`
- `MissingItemRange` (line 59) `func (b unknownBody) MissingItemRange(`
- `fixupContent` (line 63) `func (b unknownBody) fixupContent(`
- `fixupAttrs` (line 78) `func (b unknownBody) fixupAttrs(`

**Structs:**
- `unknownBody` (line 17) - *unknownBody is a funny body that just reports everything inside it as unknown. It uses a given other body as a sort of template for what attributes...*

#### `variables.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go`

**Functions:**
- `WalkVariables` (line 19) `func WalkVariables(` - *WalkVariables begins the recursive process of walking all expressions and nested blocks in the given body and its child bodies while taking into ac...*
- `WalkExpandVariables` (line 32) `func WalkExpandVariables(` - *WalkExpandVariables is like Variables but it includes only the variables required for successful block expansion, ignoring any variables referenced...*
- `Body` (line 58) `func (c WalkVariablesChild) Body(` - *Body returns the HCL Body associated with the child node, in case the caller wants to do some sort of inspection of it in order to decide what sche...*
- `Visit` (line 70) `func (n WalkVariablesNode) Visit(` - *Visit returns the variable traversals required for any "dynamic" blocks directly in the body associated with this node, and also returns any child ...*
- `extendSchema` (line 172) `func (n WalkVariablesNode) extendSchema(`

**Structs:**
- `WalkVariablesNode` (line 38)
- `WalkVariablesChild` (line 45)

#### `variables_hcldec.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go`

**Functions:**
- `VariablesHCLDec` (line 16) `func VariablesHCLDec(` - *VariablesHCLDec is a wrapper around WalkVariables that uses the given hcldec specification to automatically drive the recursive walk through nested...*
- `ExpandVariablesHCLDec` (line 25) `func ExpandVariablesHCLDec(` - *ExpandVariablesHCLDec is like VariablesHCLDec but it includes only the minimal set of variables required to call Expand, ignoring variables that ar...*
- `walkVariablesWithHCLDec` (line 30) `func walkVariablesWithHCLDec(`

#### `variables_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go`

**Functions:**
- `TestVariables` (line 16) `func TestVariables(`

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/transform/doc.go`

*No symbols extracted*

#### `error.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/transform/error.go`

**Functions:**
- `NewErrorBody` (line 17) `func NewErrorBody(` - *NewErrorBody returns a hcl.Body that returns the given diagnostics whenever any of its content-access methods are called.  The given diagnostics mu...*
- `BodyWithDiagnostics` (line 39) `func BodyWithDiagnostics(` - *BodyWithDiagnostics returns a hcl.Body that wraps another hcl.Body and emits the given diagnostics for any content-extraction method.  Unlike the r...*
- `Content` (line 56) `func (b diagBody) Content(`
- `PartialContent` (line 68) `func (b diagBody) PartialContent(`
- `JustAttributes` (line 80) `func (b diagBody) JustAttributes(`
- `MissingItemRange` (line 92) `func (b diagBody) MissingItemRange(`
- `emptyContent` (line 104) `func (b diagBody) emptyContent(`

**Structs:**
- `diagBody` (line 51)

#### `transform.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/transform/transform.go`

**Functions:**
- `Shallow` (line 9) `func Shallow(` - *Shallow is equivalent to calling transformer.TransformBody(body), and is provided only for completeness of the top-level API.*
- `Deep` (line 24) `func Deep(` - *Deep applies the given transform to the given body and then wraps the result such that any descendent blocks that are decoded will also have the tr...*
- `Content` (line 39) `func (w deepWrapper) Content(`
- `PartialContent` (line 45) `func (w deepWrapper) PartialContent(`
- `transformContent` (line 51) `func (w deepWrapper) transformContent(`
- `JustAttributes` (line 76) `func (w deepWrapper) JustAttributes(`
- `MissingItemRange` (line 81) `func (w deepWrapper) MissingItemRange(`

**Structs:**
- `deepWrapper` (line 34) - *deepWrapper is a hcl.Body implementation that ensures that a given transformer is applied to another given body when content is extracted, and that...*

#### `transform_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/transform/transform_test.go`

**Functions:**
- `TestDeep` (line 16) `func TestDeep(`

#### `transformer.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/transform/transformer.go`

**Functions:**
- `TransformBody` (line 23) `func (f TransformerFunc) TransformBody(` - *TransformBody is an implementation of Transformer.TransformBody.*
- `Chain` (line 31) `func Chain(` - *Chain takes a slice of transformers and returns a single new Transformer that applies each of the given transformers in sequence.*
- `TransformBody` (line 35) `func (c chain) TransformBody(`

**Interfaces:**
- `Transformer` (line 15) - *A Transformer takes a given body, applies some (possibly no-op) transform to it, and returns the new body.  It must _not_ mutate the given body in-...*

#### `tryfunc.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go`

**Functions:**
- `init` (line 30) `func init(`
- `try` (line 61) `func try(`
- `can` (line 109) `func can(`
- `dependsOnUnknowns` (line 130) `func dependsOnUnknowns(` - *dependsOnUnknowns returns true if any of the variables that the given expression might access are unknown values or contain unknown values.  This i...*

#### `tryfunc_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go`

**Functions:**
- `TestTryFunc` (line 12) `func TestTryFunc(`
- `TestCanFunc` (line 169) `func TestCanFunc(`

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/doc.go`

*No symbols extracted*

#### `get_type.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go`

**Functions:**
- `getType` (line 15) `func getType(` - *getType is the internal implementation of both Type and TypeConstraint, using the passed flag to distinguish. When constraint is false, the "any" k...*

#### `get_type_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go`

**Functions:**
- `TestGetType` (line 14) `func TestGetType(`
- `TestGetTypeJSON` (line 282) `func TestGetTypeJSON(`

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go`

**Functions:**
- `Type` (line 17) `func Type(` - *Type attempts to process the given expression as a type expression and, if successful, returns the resulting type. If unsuccessful, error diagnosti...*
- `TypeConstraint` (line 28) `func TypeConstraint(` - *TypeConstraint attempts to parse the given expression as a type constraint and, if successful, returns the resulting type. If unsuccessful, error d...*
- `TypeString` (line 44) `func TypeString(` - *TypeString returns a string rendering of the given type as it would be expected to appear in the HCL native syntax.  This is primarily intended for...*

#### `type_string_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go`

**Functions:**
- `TestTypeString` (line 9) `func TestTypeString(`

#### `type_type.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`

**Functions:**
- `TypeConstraintVal` (line 26) `func TypeConstraintVal(` - *TypeConstraintVal constructs a cty.Value whose type is TypeConstraintType.*
- `TypeConstraintFromVal` (line 35) `func TypeConstraintFromVal(` - *TypeConstraintFromVal extracts the type from a cty.Value of TypeConstraintType that was previously constructed using TypeConstraintVal.  If the giv...*
- `init` (line 57) `func init(`

#### `type_type_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go`

**Functions:**
- `TestTypeConstraintType` (line 10) `func TestTypeConstraintType(`
- `TestConvertFunc` (line 30) `func TestConvertFunc(`

#### `decode.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/userfunc/decode.go`

**Functions:**
- `decodeUserFunctions` (line 26) `func decodeUserFunctions(`

#### `decode_test.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/userfunc/decode_test.go`

**Functions:**
- `TestDecodeUserFunctions` (line 12) `func TestDecodeUserFunctions(`

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/userfunc/doc.go`

*No symbols extracted*

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/ext/userfunc/public.go`

**Functions:**
- `DecodeUserFunctions` (line 40) `func DecodeUserFunctions(` - *along with a new body that represents the remaining content of the given body which can be used for further processing.  The result expression of e...*

#### `decode.go`
**Path:** `teamserver/pkg/profile/yaotl/gohcl/decode.go`

**Functions:**
- `DecodeBody` (line 30) `func DecodeBody(` - *a map, where in the former case the configuration will be decoded using struct tags and in the latter case only attributes are allowed and their va...*
- `decodeBodyToValue` (line 39) `func decodeBodyToValue(`
- `decodeBodyToStruct` (line 51) `func decodeBodyToStruct(`
- `decodeBodyToMap` (line 234) `func decodeBodyToMap(`
- `decodeBlockToValue` (line 260) `func decodeBlockToValue(`
- `DecodeExpression` (line 306) `func DecodeExpression(` - *DecodeExpression extracts the value of the given expression into the given value. This value must be something that gocty is able to decode into, s...*

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/gohcl/doc.go`

*No symbols extracted*

#### `encode.go`
**Path:** `teamserver/pkg/profile/yaotl/gohcl/encode.go`

**Functions:**
- `EncodeIntoBody` (line 36) `func EncodeIntoBody(` - *Any fields tagged as "label" are ignored by this function. Use EncodeAsBlock to produce a whole hclwrite.Block including block labels.  As long as ...*
- `EncodeAsBlock` (line 60) `func EncodeAsBlock(` - *EncodeAsBlock creates a new hclwrite.Block populated with the data from the given value, which must be a struct or pointer to struct with the struc...*
- `populateBody` (line 85) `func populateBody(`

#### `schema.go`
**Path:** `teamserver/pkg/profile/yaotl/gohcl/schema.go`

**Functions:**
- `ImpliedBodySchema` (line 22) `func ImpliedBodySchema(` - *ImpliedBodySchema produces a hcl.BodySchema derived from the type of the given value, which must be a struct value or a pointer to one. If an inapp...*
- `getFieldTags` (line 125) `func getFieldTags(`

**Structs:**
- `fieldTags` (line 111)
- `labelField` (line 120)

#### `types.go`
**Path:** `teamserver/pkg/profile/yaotl/gohcl/types.go`

*No symbols extracted*

#### `block_labels.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/block_labels.go`

**Functions:**
- `labelsForBlock` (line 12) `func labelsForBlock(`

**Structs:**
- `blockLabel` (line 7)

#### `decode.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/decode.go`

**Functions:**
- `decode` (line 8) `func decode(`
- `impliedType` (line 27) `func impliedType(`
- `sourceRange` (line 31) `func sourceRange(`

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/doc.go`

*No symbols extracted*

#### `gob.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/gob.go`

**Functions:**
- `init` (line 7) `func init(`

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/public.go`

**Functions:**
- `Decode` (line 14) `func Decode(` - *Decode interprets the given body using the given specification and returns the resulting value. If the given body is not valid per the spec, error ...*
- `PartialDecode` (line 25) `func PartialDecode(` - *PartialDecode is like Decode except that it permits "leftover" items in the top-level body, which are returned as a new body to allow for further p...*
- `ImpliedType` (line 31) `func ImpliedType(` - *ImpliedType returns the value type that should result from decoding the given spec.*
- `SourceRange` (line 51) `func SourceRange(` - *fulfill the spec.  This can be used if application-level validation detects value errors, to obtain a reasonable SourceRange to use for generated d...*
- `ChildBlockTypes` (line 58) `func ChildBlockTypes(` - *ChildBlockTypes returns a map of all of the child block types declared by the given spec, with block type names as keys and the associated nested b...*

#### `public_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/public_test.go`

**Functions:**
- `TestDecode` (line 13) `func TestDecode(`
- `TestSourceRange` (line 1046) `func TestSourceRange(`

#### `schema.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/schema.go`

**Functions:**
- `ImpliedSchema` (line 10) `func ImpliedSchema(` - *ImpliedSchema returns the *hcl.BodySchema implied by the given specification. This is the schema that the Decode function will use internally to ac...*

#### `spec.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/spec.go`

**Functions:**
- `visitSameBodyChildren` (line 73) `func (s ObjectSpec) visitSameBodyChildren(`
- `decode` (line 79) `func (s ObjectSpec) decode(`
- `impliedType` (line 92) `func (s ObjectSpec) impliedType(`
- `sourceRange` (line 104) `func (s ObjectSpec) sourceRange(`
- `visitSameBodyChildren` (line 115) `func (s TupleSpec) visitSameBodyChildren(`
- `decode` (line 121) `func (s TupleSpec) decode(`
- `impliedType` (line 134) `func (s TupleSpec) impliedType(`
- `sourceRange` (line 146) `func (s TupleSpec) sourceRange(`
- `visitSameBodyChildren` (line 162) `func (s *AttrSpec) visitSameBodyChildren(`
- `variablesNeeded` (line 167) `func (s *AttrSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `attrSchemata` (line 177) `func (s *AttrSpec) attrSchemata(` - *attrSpec implementation*
- `sourceRange` (line 186) `func (s *AttrSpec) sourceRange(`
- `decode` (line 195) `func (s *AttrSpec) decode(`
- `impliedType` (line 237) `func (s *AttrSpec) impliedType(`
- `visitSameBodyChildren` (line 247) `func (s *LiteralSpec) visitSameBodyChildren(`
- `decode` (line 251) `func (s *LiteralSpec) decode(`
- `impliedType` (line 255) `func (s *LiteralSpec) impliedType(`
- `sourceRange` (line 259) `func (s *LiteralSpec) sourceRange(`
- `visitSameBodyChildren` (line 273) `func (s *ExprSpec) visitSameBodyChildren(`
- `variablesNeeded` (line 278) `func (s *ExprSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 282) `func (s *ExprSpec) decode(`
- `impliedType` (line 286) `func (s *ExprSpec) impliedType(`
- `sourceRange` (line 291) `func (s *ExprSpec) sourceRange(`
- `visitSameBodyChildren` (line 307) `func (s *BlockSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 312) `func (s *BlockSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 322) `func (s *BlockSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 327) `func (s *BlockSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 345) `func (s *BlockSpec) decode(`
- `impliedType` (line 392) `func (s *BlockSpec) impliedType(`
- `sourceRange` (line 396) `func (s *BlockSpec) sourceRange(`
- `visitSameBodyChildren` (line 423) `func (s *BlockListSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 428) `func (s *BlockListSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 438) `func (s *BlockListSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 443) `func (s *BlockListSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 457) `func (s *BlockListSpec) decode(`
- `impliedType` (line 547) `func (s *BlockListSpec) impliedType(`
- `sourceRange` (line 551) `func (s *BlockListSpec) sourceRange(`
- `visitSameBodyChildren` (line 585) `func (s *BlockTupleSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 590) `func (s *BlockTupleSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 600) `func (s *BlockTupleSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 605) `func (s *BlockTupleSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 619) `func (s *BlockTupleSpec) decode(`
- `impliedType` (line 671) `func (s *BlockTupleSpec) impliedType(`
- `sourceRange` (line 677) `func (s *BlockTupleSpec) sourceRange(`
- `visitSameBodyChildren` (line 707) `func (s *BlockSetSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 712) `func (s *BlockSetSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 722) `func (s *BlockSetSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 727) `func (s *BlockSetSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 741) `func (s *BlockSetSpec) decode(`
- `impliedType` (line 832) `func (s *BlockSetSpec) impliedType(`
- `sourceRange` (line 836) `func (s *BlockSetSpec) sourceRange(`
- `visitSameBodyChildren` (line 868) `func (s *BlockMapSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 873) `func (s *BlockMapSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 883) `func (s *BlockMapSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 888) `func (s *BlockMapSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 902) `func (s *BlockMapSpec) decode(`
- `impliedType` (line 981) `func (s *BlockMapSpec) impliedType(`
- `sourceRange` (line 989) `func (s *BlockMapSpec) sourceRange(`
- `visitSameBodyChildren` (line 1025) `func (s *BlockObjectSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 1030) `func (s *BlockObjectSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 1040) `func (s *BlockObjectSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 1045) `func (s *BlockObjectSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 1059) `func (s *BlockObjectSpec) decode(`
- `impliedType` (line 1135) `func (s *BlockObjectSpec) impliedType(`
- `sourceRange` (line 1141) `func (s *BlockObjectSpec) sourceRange(`
- `visitSameBodyChildren` (line 1183) `func (s *BlockAttrsSpec) visitSameBodyChildren(`
- `blockHeaderSchemata` (line 1188) `func (s *BlockAttrsSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 1198) `func (s *BlockAttrsSpec) nestedSpec(` - *blockSpec implementation*
- `variablesNeeded` (line 1208) `func (s *BlockAttrsSpec) variablesNeeded(` - *specNeedingVariables implementation*
- `decode` (line 1235) `func (s *BlockAttrsSpec) decode(`
- `impliedType` (line 1306) `func (s *BlockAttrsSpec) impliedType(`
- `sourceRange` (line 1310) `func (s *BlockAttrsSpec) sourceRange(`
- `findBlock` (line 1318) `func (s *BlockAttrsSpec) findBlock(`
- `visitSameBodyChildren` (line 1348) `func (s *BlockLabelSpec) visitSameBodyChildren(`
- `decode` (line 1352) `func (s *BlockLabelSpec) decode(`
- `impliedType` (line 1360) `func (s *BlockLabelSpec) impliedType(`
- `sourceRange` (line 1364) `func (s *BlockLabelSpec) sourceRange(`
- `findLabelSpecs` (line 1372) `func findLabelSpecs(`
- `visitSameBodyChildren` (line 1430) `func (s *DefaultSpec) visitSameBodyChildren(`
- `decode` (line 1435) `func (s *DefaultSpec) decode(`
- `impliedType` (line 1445) `func (s *DefaultSpec) impliedType(`
- `attrSchemata` (line 1450) `func (s *DefaultSpec) attrSchemata(` - *attrSpec implementation*
- `blockHeaderSchemata` (line 1464) `func (s *DefaultSpec) blockHeaderSchemata(` - *blockSpec implementation*
- `nestedSpec` (line 1474) `func (s *DefaultSpec) nestedSpec(` - *blockSpec implementation*
- `sourceRange` (line 1481) `func (s *DefaultSpec) sourceRange(`
- `visitSameBodyChildren` (line 1503) `func (s *TransformExprSpec) visitSameBodyChildren(`
- `decode` (line 1507) `func (s *TransformExprSpec) decode(`
- `impliedType` (line 1525) `func (s *TransformExprSpec) impliedType(`
- `sourceRange` (line 1535) `func (s *TransformExprSpec) sourceRange(`
- `visitSameBodyChildren` (line 1559) `func (s *TransformFuncSpec) visitSameBodyChildren(`
- `decode` (line 1563) `func (s *TransformFuncSpec) decode(`
- `impliedType` (line 1589) `func (s *TransformFuncSpec) impliedType(`
- `sourceRange` (line 1600) `func (s *TransformFuncSpec) sourceRange(`
- `visitSameBodyChildren` (line 1619) `func (s *ValidateSpec) visitSameBodyChildren(`
- `decode` (line 1623) `func (s *ValidateSpec) decode(`
- `impliedType` (line 1644) `func (s *ValidateSpec) impliedType(`
- `sourceRange` (line 1648) `func (s *ValidateSpec) sourceRange(`
- `decode` (line 1658) `func (s noopSpec) decode(`
- `impliedType` (line 1662) `func (s noopSpec) impliedType(`
- `visitSameBodyChildren` (line 1666) `func (s noopSpec) visitSameBodyChildren(`
- `sourceRange` (line 1670) `func (s noopSpec) sourceRange(`

**Interfaces:**
- `Spec` (line 20) - *A Spec is a description of how to decode a hcl.Body to a cty.Value.  The various other types in this package whose names end in "Spec" are the spec...*
- `attrSpec` (line 51) - *attrSpec is implemented by specs that require attributes from the body.*
- `blockSpec` (line 56) - *blockSpec is implemented by specs that require blocks from the body.*
- `specNeedingVariables` (line 63) - *specNeedingVariables is implemented by specs that can use variables from the EvalContext, to declare which variables they need.*
- `UnknownBody` (line 69) - *UnknownBody can be optionally implemented by an hcl.Body instance which may be entirely unknown.*

**Structs:**
- `AttrSpec` (line 156) - *An AttrSpec is a Spec that evaluates a particular attribute expression in the body and returns its resulting value converted to the requested type,...*
- `LiteralSpec` (line 243) - *A LiteralSpec is a Spec that produces the given literal value, ignoring the given body.*
- `ExprSpec` (line 269) - *An ExprSpec is a Spec that evaluates the given expression, ignoring the given body.*
- `BlockSpec` (line 301) - *A BlockSpec is a Spec that produces a cty.Value by decoding the contents of a single nested block of a given type, using a nested spec.  If the Req...*
- `BlockListSpec` (line 416) - *A BlockListSpec is a Spec that produces a cty list of the results of decoding all of the nested blocks of a given type, using a nested spec.*
- `BlockTupleSpec` (line 578) - *A BlockTupleSpec is a Spec that produces a cty tuple of the results of decoding all of the nested blocks of a given type, using a nested spec.  Thi...*
- `BlockSetSpec` (line 700) - *A BlockSetSpec is a Spec that produces a cty set of the results of decoding all of the nested blocks of a given type, using a nested spec.*
- `BlockMapSpec` (line 862) - *A BlockMapSpec is a Spec that produces a cty map of the results of decoding all of the nested blocks of a given type, using a nested spec.  One lev...*
- `BlockObjectSpec` (line 1019) - *A BlockObjectSpec is a Spec that produces a cty object of the results of decoding all of the nested blocks of a given type, using a nested spec.  O...*
- `BlockAttrsSpec` (line 1177) - *a map of some element type. That is, each attribute within the block becomes a key in the resulting map and the attribute's value becomes the eleme...*
- `BlockLabelSpec` (line 1343) - *A BlockLabelSpec is a Spec that returns a cty.String representing the label of the block its given body belongs to, if indeed its given body belong...*
- `DefaultSpec` (line 1425) - *and then evaluating the default if the primary returns a null value.  The two specifications must have the same implied result type for correct ope...*
- `TransformExprSpec` (line 1496) - *TransformExprSpec is a spec that wraps another and then evaluates a given hcl.Expression on the result.  The implied type of this spec is determine...*
- `TransformFuncSpec` (line 1554) - *TransformFuncSpec is a spec that wraps another and then evaluates a given cty function with the result. The given function must expect exactly one ...*
- `ValidateSpec` (line 1614) - *ValidateFuncSpec is a spec that allows for extended developer-defined validation. The validation function receives the result of the wrapped spec. ...*
- `noopSpec` (line 1655) - *noopSpec is a placeholder spec that does nothing, used in situations where a non-nil placeholder spec is required. It is not exported because there...*

#### `spec_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/spec_test.go`

**Functions:**
- `TestDefaultSpec` (line 49) `func TestDefaultSpec(`
- `TestValidateFuncSpec` (line 145) `func TestValidateFuncSpec(`

#### `variables.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/variables.go`

**Functions:**
- `Variables` (line 17) `func Variables(` - *Variables processes the given body with the given spec and returns a list of the variable traversals that would be required to decode the same pair...*

#### `variables_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hcldec/variables_test.go`

**Functions:**
- `TestVariables` (line 13) `func TestVariables(`

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/hcled/doc.go`

*No symbols extracted*

#### `navigation.go`
**Path:** `teamserver/pkg/profile/yaotl/hcled/navigation.go`

**Functions:**
- `ContextString` (line 15) `func ContextString(` - *ContextString returns a string describing the context of the given byte offset, if available. An empty string is returned if no such information is...*
- `ContextDefRange` (line 26) `func ContextDefRange(`

**Interfaces:**
- `contextStringer` (line 7)
- `contextDefRanger` (line 22)

#### `parser.go`
**Path:** `teamserver/pkg/profile/yaotl/hclparse/parser.go`

**Functions:**
- `NewParser` (line 43) `func NewParser(` - *NewParser creates a new parser, ready to parse configuration files.*
- `ParseHCL` (line 52) `func (p *Parser) ParseHCL(` - *ParseHCL parses the given buffer (which is assumed to have been loaded from the given filename) as a native-syntax configuration file and returns t...*
- `ParseHCLFile` (line 65) `func (p *Parser) ParseHCLFile(` - *ParseHCLFile reads the given filename and parses it as a native-syntax HCL configuration file. An error diagnostic is returned if the given file ca...*
- `ParseJSON` (line 86) `func (p *Parser) ParseJSON(` - *ParseJSON parses the given JSON buffer (which is assumed to have been loaded from the given filename) and returns the hcl.File object representing it.*
- `ParseJSONFile` (line 98) `func (p *Parser) ParseJSONFile(` - *ParseJSONFile reads the given filename and parses it as JSON, similarly to ParseJSON. An error diagnostic is returned if the given file cannot be r...*
- `AddFile` (line 110) `func (p *Parser) AddFile(` - *AddFile allows a caller to record in a parser a file that was parsed some other way, thus allowing it to be included in the registry of sources.*
- `Sources` (line 119) `func (p *Parser) Sources(` - *Sources returns a map from filenames to the raw source code that was read from them. This is intended to be used, for example, to print diagnostics...*
- `Files` (line 133) `func (p *Parser) Files(` - *Files returns a map from filenames to the File objects produced from them. This is intended to be used, for example, to print diagnostics with cont...*

**Structs:**
- `Parser` (line 38) - *Parser is the main interface for parsing configuration files. As well as parsing files, a parser also retains a registry of all of the files it has...*

#### `hclsimple.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`

**Functions:**
- `Decode` (line 53) `func Decode(` - *can just pass nil.  The "target" argument must be a pointer to a value of a struct type, with struct tags as defined by the sibling package "gohcl"...*
- `DecodeFile` (line 72) `func DecodeFile(` - *DecodeFile is a wrapper around Decode that first reads the given filename from disk. See the Decode documentation for more information.*

#### `diagnostics.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go`

**Functions:**
- `setDiagEvalContext` (line 16) `func setDiagEvalContext(` - *setDiagEvalContext is an internal helper that will impose a particular EvalContext on a set of diagnostics in-place, for any diagnostic that does n...*

#### `didyoumean.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go`

**Functions:**
- `nameSuggestion` (line 16) `func nameSuggestion(` - *nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns it if found. If no suggesti...*

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/doc.go`

*No symbols extracted*

#### `expression.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/expression.go`

**Functions:**
- `Range` (line 45) `func (e *ParenthesesExpr) Range(`
- `walkChildNodes` (line 49) `func (e *ParenthesesExpr) walkChildNodes(`
- `walkChildNodes` (line 62) `func (e *LiteralValueExpr) walkChildNodes(`
- `Value` (line 66) `func (e *LiteralValueExpr) Value(`
- `Range` (line 70) `func (e *LiteralValueExpr) Range(`
- `StartRange` (line 74) `func (e *LiteralValueExpr) StartRange(`
- `AsTraversal` (line 79) `func (e *LiteralValueExpr) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr.*
- `walkChildNodes` (line 130) `func (e *ScopeTraversalExpr) walkChildNodes(`
- `Value` (line 134) `func (e *ScopeTraversalExpr) Value(`
- `Range` (line 140) `func (e *ScopeTraversalExpr) Range(`
- `StartRange` (line 144) `func (e *ScopeTraversalExpr) StartRange(`
- `AsTraversal` (line 149) `func (e *ScopeTraversalExpr) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr.*
- `walkChildNodes` (line 161) `func (e *RelativeTraversalExpr) walkChildNodes(`
- `Value` (line 165) `func (e *RelativeTraversalExpr) Value(`
- `Range` (line 173) `func (e *RelativeTraversalExpr) Range(`
- `StartRange` (line 177) `func (e *RelativeTraversalExpr) StartRange(`
- `AsTraversal` (line 182) `func (e *RelativeTraversalExpr) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr.*
- `walkChildNodes` (line 210) `func (e *FunctionCallExpr) walkChildNodes(`
- `Value` (line 216) `func (e *FunctionCallExpr) Value(`
- `Range` (line 541) `func (e *FunctionCallExpr) Range(`
- `StartRange` (line 545) `func (e *FunctionCallExpr) StartRange(`
- `ExprCall` (line 550) `func (e *FunctionCallExpr) ExprCall(` - *Implementation for hcl.ExprCall.*
- `walkChildNodes` (line 572) `func (e *ConditionalExpr) walkChildNodes(`
- `Value` (line 578) `func (e *ConditionalExpr) Value(`
- `Range` (line 715) `func (e *ConditionalExpr) Range(`
- `StartRange` (line 719) `func (e *ConditionalExpr) StartRange(`
- `walkChildNodes` (line 732) `func (e *IndexExpr) walkChildNodes(`
- `Value` (line 737) `func (e *IndexExpr) Value(`
- `Range` (line 750) `func (e *IndexExpr) Range(`
- `StartRange` (line 754) `func (e *IndexExpr) StartRange(`
- `walkChildNodes` (line 765) `func (e *TupleConsExpr) walkChildNodes(`
- `Value` (line 771) `func (e *TupleConsExpr) Value(`
- `Range` (line 785) `func (e *TupleConsExpr) Range(`
- `StartRange` (line 789) `func (e *TupleConsExpr) StartRange(`
- `ExprList` (line 794) `func (e *TupleConsExpr) ExprList(` - *Implementation for hcl.ExprList*
- `walkChildNodes` (line 814) `func (e *ObjectConsExpr) walkChildNodes(`
- `Value` (line 821) `func (e *ObjectConsExpr) Value(`
- `Range` (line 897) `func (e *ObjectConsExpr) Range(`
- `StartRange` (line 901) `func (e *ObjectConsExpr) StartRange(`
- `ExprMap` (line 906) `func (e *ObjectConsExpr) ExprMap(` - *Implementation for hcl.ExprMap*
- `literalName` (line 925) `func (e *ObjectConsKeyExpr) literalName(`
- `walkChildNodes` (line 934) `func (e *ObjectConsKeyExpr) walkChildNodes(`
- `Value` (line 942) `func (e *ObjectConsKeyExpr) Value(`
- `Range` (line 971) `func (e *ObjectConsKeyExpr) Range(`
- `StartRange` (line 975) `func (e *ObjectConsKeyExpr) StartRange(`
- `AsTraversal` (line 980) `func (e *ObjectConsKeyExpr) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr.*
- `UnwrapExpression` (line 996) `func (e *ObjectConsKeyExpr) UnwrapExpression(`
- `Value` (line 1022) `func (e *ForExpr) Value(`
- `walkChildNodes` (line 1346) `func (e *ForExpr) walkChildNodes(`
- `Range` (line 1375) `func (e *ForExpr) Range(`
- `StartRange` (line 1379) `func (e *ForExpr) StartRange(`
- `Value` (line 1392) `func (e *SplatExpr) Value(`
- `walkChildNodes` (line 1522) `func (e *SplatExpr) walkChildNodes(`
- `Range` (line 1527) `func (e *SplatExpr) Range(`
- `StartRange` (line 1531) `func (e *SplatExpr) StartRange(`
- `Value` (line 1558) `func (e *AnonSymbolExpr) Value(`
- `setValue` (line 1575) `func (e *AnonSymbolExpr) setValue(` - *setValue sets a temporary local value for the expression when evaluated in the given context, which must be non-nil.*
- `clearValue` (line 1588) `func (e *AnonSymbolExpr) clearValue(`
- `walkChildNodes` (line 1601) `func (e *AnonSymbolExpr) walkChildNodes(`
- `Range` (line 1605) `func (e *AnonSymbolExpr) Range(`
- `StartRange` (line 1609) `func (e *AnonSymbolExpr) StartRange(`

**Interfaces:**
- `Expression` (line 15) - *Expression is the abstract type for nodes that behave as HCL expressions.*

**Structs:**
- `ParenthesesExpr` (line 38) - *ParenthesesExpr represents an expression written in grouping parentheses.  The parser takes care of the precedence effect of the parentheses, so th...*
- `LiteralValueExpr` (line 57) - *LiteralValueExpr is an expression that just always returns a given value.*
- `ScopeTraversalExpr` (line 125) - *ScopeTraversalExpr is an Expression that retrieves a value from the scope using a traversal.*
- `RelativeTraversalExpr` (line 155) - *RelativeTraversalExpr is an Expression that retrieves a value from another value using a _relative_ traversal.*
- `FunctionCallExpr` (line 197) - *FunctionCallExpr is an Expression that calls a function from the EvalContext and returns its result.*
- `ConditionalExpr` (line 564)
- `IndexExpr` (line 723)
- `TupleConsExpr` (line 758)
- `ObjectConsExpr` (line 802)
- `ObjectConsItem` (line 809)
- `ObjectConsKeyExpr` (line 920) - *ObjectConsKeyExpr is a special wrapper used only for ObjectConsExpr keys, which deals with the special case that a naked identifier in that positio...*
- `ForExpr` (line 1005) - *ForExpr represents iteration constructs:  tuple = [for i, v in list: upper(v) if i > 2] object = {for k, v in map: k => upper(v)} object_of_tuples ...*
- `SplatExpr` (line 1383)
- `AnonSymbolExpr` (line 1546) - *AnonSymbolExpr is used as a placeholder for a value in an expression that can be applied dynamically to any value at runtime.  This is a rather odd...*

#### `expression_ops.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go`

**Functions:**
- `init` (line 86) `func init(`
- `walkChildNodes` (line 131) `func (e *BinaryOpExpr) walkChildNodes(`
- `Value` (line 136) `func (e *BinaryOpExpr) Value(`
- `Range` (line 198) `func (e *BinaryOpExpr) Range(`
- `StartRange` (line 202) `func (e *BinaryOpExpr) StartRange(`
- `walkChildNodes` (line 214) `func (e *UnaryOpExpr) walkChildNodes(`
- `Value` (line 218) `func (e *UnaryOpExpr) Value(`
- `Range` (line 262) `func (e *UnaryOpExpr) Range(`
- `StartRange` (line 266) `func (e *UnaryOpExpr) StartRange(`

**Structs:**
- `Operation` (line 13)
- `BinaryOpExpr` (line 123)
- `UnaryOpExpr` (line 206)

#### `expression_template.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go`

**Functions:**
- `walkChildNodes` (line 18) `func (e *TemplateExpr) walkChildNodes(`
- `Value` (line 24) `func (e *TemplateExpr) Value(`
- `Range` (line 97) `func (e *TemplateExpr) Range(`
- `StartRange` (line 101) `func (e *TemplateExpr) StartRange(`
- `IsStringLiteral` (line 117) `func (e *TemplateExpr) IsStringLiteral(` - *IsStringLiteral returns true if and only if the template consists only of single string literal, as would be created for a simple quoted string lik...*
- `walkChildNodes` (line 133) `func (e *TemplateJoinExpr) walkChildNodes(`
- `Value` (line 137) `func (e *TemplateJoinExpr) Value(`
- `Range` (line 207) `func (e *TemplateJoinExpr) Range(`
- `StartRange` (line 211) `func (e *TemplateJoinExpr) StartRange(`
- `walkChildNodes` (line 225) `func (e *TemplateWrapExpr) walkChildNodes(`
- `Value` (line 229) `func (e *TemplateWrapExpr) Value(`
- `Range` (line 233) `func (e *TemplateWrapExpr) Range(`
- `StartRange` (line 237) `func (e *TemplateWrapExpr) StartRange(`

**Structs:**
- `TemplateExpr` (line 12)
- `TemplateJoinExpr` (line 129) - *TemplateJoinExpr is used to convert tuples of strings produced by template constructs (i.e. for loops) into flat strings, by converting the values ...*
- `TemplateWrapExpr` (line 219) - *TemplateWrapExpr is used instead of a TemplateExpr when a template consists _only_ of a single interpolation sequence. In that case, the template's...*

#### `expression_vars.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go`

**Functions:**
- `Variables` (line 10) `func (e *AnonSymbolExpr) Variables(`
- `Variables` (line 14) `func (e *BinaryOpExpr) Variables(`
- `Variables` (line 18) `func (e *ConditionalExpr) Variables(`
- `Variables` (line 22) `func (e *ForExpr) Variables(`
- `Variables` (line 26) `func (e *FunctionCallExpr) Variables(`
- `Variables` (line 30) `func (e *IndexExpr) Variables(`
- `Variables` (line 34) `func (e *LiteralValueExpr) Variables(`
- `Variables` (line 38) `func (e *ObjectConsExpr) Variables(`
- `Variables` (line 42) `func (e *ObjectConsKeyExpr) Variables(`
- `Variables` (line 46) `func (e *RelativeTraversalExpr) Variables(`
- `Variables` (line 50) `func (e *ScopeTraversalExpr) Variables(`
- `Variables` (line 54) `func (e *SplatExpr) Variables(`
- `Variables` (line 58) `func (e *TemplateExpr) Variables(`
- `Variables` (line 62) `func (e *TemplateJoinExpr) Variables(`
- `Variables` (line 66) `func (e *TemplateWrapExpr) Variables(`
- `Variables` (line 70) `func (e *TupleConsExpr) Variables(`
- `Variables` (line 74) `func (e *UnaryOpExpr) Variables(`

#### `expression_vars_gen.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

**Functions:**
- `main` (line 20) `func main(`
- `Variables` (line 97) `func (e %s) Variables(`

#### `file.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/file.go`

**Functions:**
- `AsHCLFile` (line 13) `func (f *File) AsHCLFile(`

**Structs:**
- `File` (line 8) - *File is the top-level object resulting from parsing a configuration file.*

#### `fuzz.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go`

**Functions:**
- `Fuzz` (line 8) `func Fuzz(`

#### `fuzz.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go`

**Functions:**
- `Fuzz` (line 8) `func Fuzz(`

#### `fuzz.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go`

**Functions:**
- `Fuzz` (line 8) `func Fuzz(`

#### `fuzz.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go`

**Functions:**
- `Fuzz` (line 8) `func Fuzz(`

#### `generate.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/generate.go`

*No symbols extracted*

#### `keywords.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/keywords.go`

**Functions:**
- `TokenMatches` (line 16) `func (kw Keyword) TokenMatches(`

#### `navigation.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go`

**Functions:**
- `ContextString` (line 15) `func (n navigation) ContextString(` - *Implementation of hcled.ContextString*
- `ContextDefRange` (line 45) `func (n navigation) ContextDefRange(`

**Structs:**
- `navigation` (line 10)

#### `node.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/node.go`

**Interfaces:**
- `Node` (line 11) - *Node is the abstract type that every AST node implements.  This is a closed interface, so it cannot be implemented from outside of this package.*

#### `parser.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/parser.go`

**Functions:**
- `ParseBody` (line 25) `func (p *parser) ParseBody(`
- `ParseBodyItem` (line 116) `func (p *parser) ParseBodyItem(`
- `parseSingleAttrBody` (line 156) `func (p *parser) parseSingleAttrBody(` - *parseSingleAttrBody is a weird variant of ParseBody that deals with the body of a nested block containing only one attribute value all on a single ...*
- `finishParsingBodyAttribute` (line 217) `func (p *parser) finishParsingBodyAttribute(`
- `finishParsingBodyBlock` (line 274) `func (p *parser) finishParsingBodyBlock(`
- `ParseExpression` (line 444) `func (p *parser) ParseExpression(`
- `parseTernaryConditional` (line 448) `func (p *parser) parseTernaryConditional(`
- `parseBinaryOps` (line 512) `func (p *parser) parseBinaryOps(` - *parseBinaryOps calls itself recursively to work through all of the operator precedence groups, and then eventually calls parseExpressionTerm for ea...*
- `parseExpressionWithTraversals` (line 584) `func (p *parser) parseExpressionWithTraversals(`
- `parseExpressionTraversals` (line 591) `func (p *parser) parseExpressionTraversals(`
- `makeRelativeTraversal` (line 891) `func makeRelativeTraversal(` - *makeRelativeTraversal takes an expression and a traverser and returns a traversal expression that combines the two. If the given expression is alre...*
- `parseExpressionTerm` (line 910) `func (p *parser) parseExpressionTerm(`
- `numberLitValue` (line 1081) `func (p *parser) numberLitValue(`
- `finishParsingFunctionCall` (line 1105) `func (p *parser) finishParsingFunctionCall(` - *finishParsingFunctionCall parses a function call assuming that the function name was already read, and so the peeker should be pointing at the open...*
- `parseTupleCons` (line 1200) `func (p *parser) parseTupleCons(`
- `parseObjectCons` (line 1270) `func (p *parser) parseObjectCons(`
- `finishParsingForExpr` (line 1427) `func (p *parser) finishParsingForExpr(`
- `parseQuotedStringLiteral` (line 1650) `func (p *parser) parseQuotedStringLiteral(` - *parseQuotedStringLiteral is a helper for parsing quoted strings that aren't allowed to contain any interpolations, such as block labels.*
- `ParseStringLiteralToken` (line 1745) `func ParseStringLiteralToken(` - *ParseStringLiteralToken processes the given token, which must be either a TokenQuotedLit or a TokenStringLit, returning the string resulting from r...*
- `setRecovery` (line 1912) `func (p *parser) setRecovery(` - *setRecovery turns on recovery mode without actually doing any recovery. This can be used when a parser knowingly leaves the peeker in a useless pla...*
- `recover` (line 1924) `func (p *parser) recover(` - *recover seeks forward in the token stream until it finds TokenType "end", then returns with the peeker pointed at the following token.  If the give...*
- `recoverOver` (line 1963) `func (p *parser) recoverOver(` - *recoverOver seeks forward in the token stream until it finds a block starting with TokenType "start", then finds the corresponding end token, leavi...*
- `recoverAfterBodyItem` (line 1981) `func (p *parser) recoverAfterBodyItem(`
- `oppositeBracket` (line 2028) `func (p *parser) oppositeBracket(` - *oppositeBracket finds the bracket that opposes the given bracketer, or NilToken if the given token isn't a bracketer.  "Bracketer", for the sake of...*
- `errPlaceholderExpr` (line 2067) `func errPlaceholderExpr(`

**Structs:**
- `parser` (line 15)

#### `parser_template.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go`

**Functions:**
- `ParseTemplate` (line 13) `func (p *parser) ParseTemplate(`
- `parseTemplate` (line 17) `func (p *parser) parseTemplate(`
- `parseTemplateInner` (line 36) `func (p *parser) parseTemplateInner(`
- `parseRoot` (line 65) `func (p *templateParser) parseRoot(`
- `parseExpr` (line 83) `func (p *templateParser) parseExpr(`
- `parseIf` (line 135) `func (p *templateParser) parseIf(`
- `parseFor` (line 247) `func (p *templateParser) parseFor(`
- `Peek` (line 344) `func (p *templateParser) Peek(`
- `Read` (line 348) `func (p *templateParser) Read(`
- `parseTemplateParts` (line 361) `func (p *parser) parseTemplateParts(` - *parseTemplateParts produces a flat sequence of "template tokens", which are either literal values (with any "trimming" already applied), interpolat...*
- `flushHeredocTemplateParts` (line 675) `func flushHeredocTemplateParts(` - *flushHeredocTemplateParts modifies in-place the line-leading literal strings to apply the flush heredoc processing rule: find the line with the sma...*
- `Name` (line 787) `func (t *templateEndCtrlToken) Name(`
- `templateToken` (line 808) `func (t isTemplateToken) templateToken(`

**Interfaces:**
- `templateToken` (line 743) - *templateToken is a higher-level token that represents a single atom within the template language. Our template parsing first raises the raw token s...*

**Structs:**
- `templateParser` (line 58)
- `templateParts` (line 734)
- `templateLiteralToken` (line 747)
- `templateInterpToken` (line 753)
- `templateIfToken` (line 759)
- `templateForToken` (line 765)
- `templateEndCtrlToken` (line 781)
- `templateEndToken` (line 801)

#### `parser_traversal.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go`

**Functions:**
- `ParseTraversalAbs` (line 12) `func (p *parser) ParseTraversalAbs(` - *ParseTraversalAbs parses an absolute traversal that is assumed to consume all of the remaining tokens in the peeker. The usual parser recovery beha...*

#### `peeker.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go`

**Functions:**
- `newPeeker` (line 38) `func newPeeker(`
- `Peek` (line 47) `func (p *peeker) Peek(`
- `Read` (line 52) `func (p *peeker) Read(`
- `NextRange` (line 58) `func (p *peeker) NextRange(`
- `PrevRange` (line 62) `func (p *peeker) PrevRange(`
- `nextToken` (line 70) `func (p *peeker) nextToken(`
- `includingNewlines` (line 118) `func (p *peeker) includingNewlines(`
- `PushIncludeNewlines` (line 122) `func (p *peeker) PushIncludeNewlines(`
- `PopIncludeNewlines` (line 138) `func (p *peeker) PopIncludeNewlines(`
- `AssertEmptyIncludeNewlinesStack` (line 168) `func (p *peeker) AssertEmptyIncludeNewlinesStack(` - *AssertEmptyNewlinesStack checks if the IncludeNewlinesStack is empty, doing panicking if it is not. This can be used to catch stack mismanagement t...*
- `formatPeekerNewlineStackChanges` (line 184) `func formatPeekerNewlineStackChanges(`

**Structs:**
- `peeker` (line 20)
- `peekerNewlineStackChange` (line 32) - *for use in debugging the stack usage only*

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/public.go`

**Functions:**
- `ParseConfig` (line 17) `func ParseConfig(` - *ParseConfig parses the given buffer as a whole HCL config file, returning a *hcl.File representing its contents. If HasErrors called on the returne...*
- `ParseExpression` (line 41) `func ParseExpression(` - *ParseExpression parses the given buffer as a standalone HCL expression, returning it as an instance of Expression.*
- `ParseTemplate` (line 75) `func ParseTemplate(` - *ParseTemplate parses the given buffer as a standalone HCL template, returning it as an instance of Expression.*
- `ParseTraversalAbs` (line 96) `func ParseTraversalAbs(` - *ParseTraversalAbs parses the given buffer as a standalone absolute traversal.  Parsing as a traversal is more limited than parsing as an expression...*
- `LexConfig` (line 125) `func LexConfig(` - *LexConfig performs lexical analysis on the given buffer, treating it as a whole HCL config file, and returns the resulting tokens.  Only minimal va...*
- `LexExpression` (line 138) `func LexExpression(` - *LexExpression performs lexical analysis on the given buffer, treating it as a standalone HCL expression, and returns the resulting tokens.  Only mi...*
- `LexTemplate` (line 153) `func LexTemplate(` - *LexTemplate performs lexical analysis on the given buffer, treating it as a standalone HCL template, and returns the resulting tokens.  Only minima...*
- `ValidIdentifier` (line 165) `func ValidIdentifier(` - *ValidIdentifier tests if the given string could be a valid identifier in a native syntax expression.  This is useful when accepting names from the ...*

#### `scan_string_lit.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go`

**Functions:**
- `scanStringLit` (line 119) `func scanStringLit(`

#### `scan_tokens.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go`

**Functions:**
- `scanTokens` (line 4220) `func scanTokens(`

#### `structure.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/structure.go`

**Functions:**
- `AsHCLBlock` (line 11) `func (b *Block) AsHCLBlock(` - *AsHCLBlock returns the block data expressed as a *hcl.Block.*
- `walkChildNodes` (line 49) `func (b *Body) walkChildNodes(`
- `Range` (line 54) `func (b *Body) Range(`
- `Content` (line 58) `func (b *Body) Content(`
- `PartialContent` (line 128) `func (b *Body) PartialContent(`
- `JustAttributes` (line 250) `func (b *Body) JustAttributes(`
- `MissingItemRange` (line 281) `func (b *Body) MissingItemRange(`
- `walkChildNodes` (line 292) `func (a Attributes) walkChildNodes(`
- `Range` (line 303) `func (a Attributes) Range(` - *Range returns the range of some arbitrary point within the set of attributes, or an invalid range if there are no attributes.  This is provided onl...*
- `walkChildNodes` (line 327) `func (a *Attribute) walkChildNodes(`
- `Range` (line 331) `func (a *Attribute) Range(`
- `AsHCLAttribute` (line 336) `func (a *Attribute) AsHCLAttribute(` - *AsHCLAttribute returns the block data expressed as a *hcl.Attribute.*
- `walkChildNodes` (line 352) `func (bs Blocks) walkChildNodes(`
- `Range` (line 363) `func (bs Blocks) Range(` - *Range returns the range of some arbitrary point within the list of blocks, or an invalid range if there are no blocks.  This is provided only to co...*
- `walkChildNodes` (line 384) `func (b *Block) walkChildNodes(`
- `Range` (line 388) `func (b *Block) Range(`
- `DefRange` (line 392) `func (b *Block) DefRange(`

**Structs:**
- `Body` (line 33) - *Body is the implementation of hcl.Body for the HCL native syntax.*
- `Attribute` (line 318) - *Attribute represents a single attribute definition within a body.*
- `Block` (line 373) - *Block represents a nested block structure*

#### `structure_at_pos.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go`

**Functions:**
- `BlocksAtPos` (line 15) `func (b *Body) BlocksAtPos(` - *BlocksAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.*
- `InnermostBlockAtPos` (line 22) `func (b *Body) InnermostBlockAtPos(` - *InnermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.*
- `OutermostBlockAtPos` (line 29) `func (b *Body) OutermostBlockAtPos(` - *OutermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.*
- `blocksAtPos` (line 40) `func (b *Body) blocksAtPos(` - *blocksAtPos is the internal engine of both BlocksAtPos and InnermostBlockAtPos, which both need to do the same logic but return a differently-shape...*
- `outermostBlockAtPos` (line 68) `func (b *Body) outermostBlockAtPos(` - *outermostBlockAtPos is the internal version of OutermostBlockAtPos that returns a hclsyntax.Block rather than an hcl.Block, allowing for further an...*
- `AttributeAtPos` (line 84) `func (b *Body) AttributeAtPos(` - *AttributeAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.*
- `attributeAtPos` (line 91) `func (b *Body) attributeAtPos(` - *attributeAtPos is the internal version of AttributeAtPos that returns a hclsyntax.Block rather than an hcl.Block, allowing for further analysis if ...*
- `OutermostExprAtPos` (line 109) `func (b *Body) OutermostExprAtPos(` - *OutermostExprAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.*

#### `token.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/token.go`

**Functions:**
- `GoString` (line 107) `func (t TokenType) GoString(`
- `emitToken` (line 127) `func (f *tokenAccum) emitToken(`
- `tokenOpensFlushHeredoc` (line 167) `func tokenOpensFlushHeredoc(`
- `checkInvalidTokens` (line 182) `func checkInvalidTokens(` - *checkInvalidTokens does a simple pass across the given tokens and generates diagnostics for tokens that should _never_ appear in HCL source. This i...*
- `stripUTF8BOM` (line 326) `func stripUTF8BOM(` - *stripUTF8BOM checks whether the given buffer begins with a UTF-8 byte order mark (0xEF 0xBB 0xBF) and, if so, returns a truncated slice with the sa...*

**Structs:**
- `Token` (line 13) - *Token represents a sequence of bytes from some HCL code that has been tagged with a type and its range within the source file.*
- `tokenAccum` (line 119)
- `heredocInProgress` (line 162)

#### `token_type_string.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go`

**Functions:**
- `_` (line 7) `func _(`
- `String` (line 126) `func (i TokenType) String(`

#### `variables.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/variables.go`

**Functions:**
- `Variables` (line 11) `func Variables(` - *Variables returns all of the variables referenced within a given expression.  This is the implementation of the "Variables" method on every native ...*
- `Enter` (line 32) `func (w *variablesWalker) Enter(`
- `Exit` (line 55) `func (w *variablesWalker) Exit(`
- `walkChildNodes` (line 78) `func (e ChildScope) walkChildNodes(`
- `Range` (line 84) `func (e ChildScope) Range(` - *Range returns the range of the expression that the ChildScope is encapsulating. It isn't really very useful to call Range on a ChildScope.*

**Structs:**
- `variablesWalker` (line 27) - *variablesWalker is a Walker implementation that calls its callback for any root scope traversal found while walking.*
- `ChildScope` (line 73) - *ChildScope is a synthetic AST node that is visited during a walk to indicate that its descendent will be evaluated in a child scope, which may mask...*

#### `walk.go`
**Path:** `teamserver/pkg/profile/yaotl/hclsyntax/walk.go`

**Functions:**
- `VisitAll` (line 16) `func VisitAll(` - *VisitAll is a basic way to traverse the AST beginning with a particular node. The given function will be called once for each AST node in depth-fir...*
- `Walk` (line 33) `func Walk(` - *Walk is a more complex way to traverse the AST starting with a particular node, which provides information about the tree structure via separate En...*

**Interfaces:**
- `Walker` (line 25) - *Walker is an interface used with Walk.*

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/hcltest/doc.go`

*No symbols extracted*

#### `mock.go`
**Path:** `teamserver/pkg/profile/yaotl/hcltest/mock.go`

**Functions:**
- `MockBody` (line 15) `func MockBody(` - *MockBody returns a hcl.Body implementation that works in terms of a caller-constructed hcl.BodyContent, thus avoiding the need to parse a "real" HC...*
- `Content` (line 23) `func (b mockBody) Content(`
- `PartialContent` (line 45) `func (b mockBody) PartialContent(`
- `JustAttributes` (line 108) `func (b mockBody) JustAttributes(`
- `MissingItemRange` (line 122) `func (b mockBody) MissingItemRange(`
- `MockExprLiteral` (line 128) `func MockExprLiteral(` - *MockExprLiteral returns a hcl.Expression that evaluates to the given literal value.*
- `Value` (line 136) `func (e mockExprLiteral) Value(`
- `Variables` (line 140) `func (e mockExprLiteral) Variables(`
- `Range` (line 144) `func (e mockExprLiteral) Range(`
- `StartRange` (line 150) `func (e mockExprLiteral) StartRange(`
- `ExprList` (line 155) `func (e mockExprLiteral) ExprList(` - *Implementation for hcl.ExprList*
- `ExprMap` (line 170) `func (e mockExprLiteral) ExprMap(` - *Implementation for hcl.ExprMap*
- `MockExprVariable` (line 189) `func MockExprVariable(` - *MockExprVariable returns a hcl.Expression that evaluates to the value of the variable with the given name.*
- `Value` (line 195) `func (e mockExprVariable) Value(`
- `Variables` (line 214) `func (e mockExprVariable) Variables(`
- `Range` (line 225) `func (e mockExprVariable) Range(`
- `StartRange` (line 231) `func (e mockExprVariable) StartRange(`
- `AsTraversal` (line 236) `func (e mockExprVariable) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr and hcl.RelTraversalForExpr.*
- `MockExprTraversal` (line 247) `func MockExprTraversal(` - *MockExprTraversal returns a hcl.Expression that evaluates the given absolute traversal.*
- `MockExprTraversalSrc` (line 258) `func MockExprTraversalSrc(` - *MockExprTraversalSrc is like MockExprTraversal except it takes a traversal string as defined by the native syntax and parses it first.  This method...*
- `Value` (line 270) `func (e mockExprTraversal) Value(`
- `Variables` (line 274) `func (e mockExprTraversal) Variables(`
- `Range` (line 278) `func (e mockExprTraversal) Range(`
- `StartRange` (line 282) `func (e mockExprTraversal) StartRange(`
- `AsTraversal` (line 287) `func (e mockExprTraversal) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr and hcl.RelTraversalForExpr.*
- `MockExprList` (line 291) `func MockExprList(`
- `Value` (line 301) `func (e mockExprList) Value(`
- `Variables` (line 317) `func (e mockExprList) Variables(`
- `Range` (line 325) `func (e mockExprList) Range(`
- `StartRange` (line 331) `func (e mockExprList) StartRange(`
- `ExprList` (line 336) `func (e mockExprList) ExprList(` - *Implementation for hcl.ExprList*
- `MockAttrs` (line 345) `func MockAttrs(` - *MockAttrs constructs and returns a hcl.Attributes map with attributes derived from the given expression map.  Each entry in the map becomes an attr...*

**Structs:**
- `mockBody` (line 19)
- `mockExprLiteral` (line 132)
- `mockExprTraversal` (line 266)
- `mockExprList` (line 297)

#### `mock_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hcltest/mock_test.go`

**Functions:**
- `TestMockBodyPartialContent` (line 17) `func TestMockBodyPartialContent(`
- `TestExprList` (line 271) `func TestExprList(`
- `TestExprMap` (line 328) `func TestExprMap(`

#### `ast.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast.go`

**Functions:**
- `NewEmptyFile` (line 17) `func NewEmptyFile(` - *NewEmptyFile constructs a new file with no content, ready to be mutated by other calls that append to its body.*
- `Body` (line 28) `func (f *File) Body(` - *Body returns the root body of the file, which contains the top-level attributes and blocks.*
- `WriteTo` (line 36) `func (f *File) WriteTo(` - *WriteTo writes the tokens underlying the receiving file to the given writer.  The tokens first have a simple formatting pass applied that adjusts o...*
- `Bytes` (line 45) `func (f *File) Bytes(` - *Bytes returns a buffer containing the source code resulting from the tokens underlying the receiving file. If any updates have been made via the AS...*
- `newComments` (line 58) `func newComments(`
- `BuildTokens` (line 64) `func (c *comments) BuildTokens(`
- `newIdentifier` (line 75) `func newIdentifier(`
- `BuildTokens` (line 81) `func (i *identifier) BuildTokens(`
- `hasName` (line 85) `func (i *identifier) hasName(`
- `newNumber` (line 96) `func newNumber(`
- `BuildTokens` (line 102) `func (n *number) BuildTokens(`
- `newQuoted` (line 113) `func newQuoted(`
- `BuildTokens` (line 119) `func (q *quoted) BuildTokens(`

**Structs:**
- `File` (line 8)
- `comments` (line 51)
- `identifier` (line 68)
- `number` (line 89)
- `quoted` (line 106)

#### `ast_attribute.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go`

**Functions:**
- `newAttribute` (line 16) `func newAttribute(`
- `init` (line 22) `func (a *Attribute) init(`
- `Expr` (line 46) `func (a *Attribute) Expr(`

**Structs:**
- `Attribute` (line 7)

#### `ast_block.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go`

**Functions:**
- `newBlock` (line 19) `func newBlock(`
- `NewBlock` (line 26) `func NewBlock(` - *NewBlock constructs a new, empty block with the given type name and labels.*
- `init` (line 32) `func (b *Block) init(`
- `Body` (line 67) `func (b *Block) Body(` - *Body returns the body that represents the content of the receiving block.  Appending to or otherwise modifying this body will make changes to the t...*
- `Type` (line 72) `func (b *Block) Type(` - *Type returns the type name of the block.*
- `SetType` (line 78) `func (b *Block) SetType(` - *SetType updates the type name of the block to a given name.*
- `Labels` (line 85) `func (b *Block) Labels(` - *Labels returns the labels of the block.*
- `SetLabels` (line 92) `func (b *Block) SetLabels(` - *SetLabels updates the labels of the block to given labels. Since we cannot assume that old and new labels are equal in length, remove old labels an...*
- `labelsObj` (line 101) `func (b *Block) labelsObj(` - *labelsObj returns the internal node content representation of the block labels. This is not part of the public API because we're intentionally expo...*
- `newBlockLabels` (line 111) `func newBlockLabels(`
- `Replace` (line 121) `func (bl *blockLabels) Replace(`
- `Current` (line 136) `func (bl *blockLabels) Current(`

**Structs:**
- `Block` (line 8)
- `blockLabels` (line 105)

#### `ast_block_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go`

**Functions:**
- `TestBlockType` (line 15) `func TestBlockType(`
- `TestBlockLabels` (line 49) `func TestBlockLabels(`
- `TestBlockSetType` (line 138) `func TestBlockSetType(`
- `TestBlockSetLabels` (line 198) `func TestBlockSetLabels(`

#### `ast_body.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go`

**Functions:**
- `newBody` (line 17) `func newBody(`
- `appendItem` (line 24) `func (b *Body) appendItem(`
- `appendItemNode` (line 30) `func (b *Body) appendItemNode(`
- `Clear` (line 38) `func (b *Body) Clear(` - *Clear removes all of the items from the body, making it empty.*
- `AppendUnstructuredTokens` (line 42) `func (b *Body) AppendUnstructuredTokens(`
- `Attributes` (line 48) `func (b *Body) Attributes(` - *Attributes returns a new map of all of the attributes in the body, with the attribute names as the keys.*
- `Blocks` (line 61) `func (b *Body) Blocks(` - *Blocks returns a new slice of all the blocks in the body.*
- `GetAttribute` (line 73) `func (b *Body) GetAttribute(` - *GetAttribute returns the attribute from the body that has the given name, or returns nil if there is currently no matching attribute.*
- `getAttributeNode` (line 89) `func (b *Body) getAttributeNode(` - *getAttributeNode is like GetAttribute but it returns the node containing the selected attribute (if one is found) rather than the attribute itself.*
- `FirstMatchingBlock` (line 106) `func (b *Body) FirstMatchingBlock(` - *FirstMatchingBlock returns a first matching block from the body that has the given name and labels or returns nil if there is currently no matching...*
- `RemoveBlock` (line 126) `func (b *Body) RemoveBlock(` - *RemoveBlock removes the given block from the body, if it's in that body. If it isn't present, this is a no-op.  Returns true if it removed somethin...*
- `SetAttributeRaw` (line 144) `func (b *Body) SetAttributeRaw(` - *SetAttributeRaw either replaces the expression of an existing attribute of the given name or adds a new attribute definition to the end of the bloc...*
- `SetAttributeValue` (line 165) `func (b *Body) SetAttributeValue(` - *SetAttributeValue either replaces the expression of an existing attribute of the given name or adds a new attribute definition to the end of the bl...*
- `SetAttributeTraversal` (line 186) `func (b *Body) SetAttributeTraversal(` - *SetAttributeTraversal either replaces the expression of an existing attribute of the given name or adds a new attribute definition to the end of th...*
- `RemoveAttribute` (line 203) `func (b *Body) RemoveAttribute(` - *RemoveAttribute removes the attribute with the given name from the body.  The return value is the attribute that was removed, or nil if there was n...*
- `AppendBlock` (line 215) `func (b *Body) AppendBlock(` - *AppendBlock appends an existing block (which must not be already attached to a body) to the end of the receiving body.*
- `AppendNewBlock` (line 222) `func (b *Body) AppendNewBlock(` - *AppendNewBlock appends a new nested block to the end of the receiving body with the given type name and labels.*
- `AppendNewline` (line 232) `func (b *Body) AppendNewline(` - *AppendNewline appends a newline token to th end of the receiving body, which generally serves as a separator between different sets of body contents.*

**Structs:**
- `Body` (line 11)

#### `ast_body_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go`

**Functions:**
- `TestBodyGetAttribute` (line 16) `func TestBodyGetAttribute(`
- `TestBodyFirstMatchingBlock` (line 220) `func TestBodyFirstMatchingBlock(`
- `TestBodySetAttributeValue` (line 345) `func TestBodySetAttributeValue(`
- `TestBodySetAttributeTraversal` (line 543) `func TestBodySetAttributeTraversal(`
- `TestBodySetAttributeRaw` (line 769) `func TestBodySetAttributeRaw(`
- `TestBodySetAttributeValueInBlock` (line 933) `func TestBodySetAttributeValueInBlock(`
- `TestBodySetAttributeValueInNestedBlock` (line 981) `func TestBodySetAttributeValueInNestedBlock(`
- `TestBodyRemoveAttribute` (line 1036) `func TestBodyRemoveAttribute(`
- `TestBodyAppendBlock` (line 1149) `func TestBodyAppendBlock(`
- `TestBodyRemoveBlock` (line 1392) `func TestBodyRemoveBlock(`

#### `ast_expression.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go`

**Functions:**
- `newExpression` (line 17) `func newExpression(`
- `NewExpressionRaw` (line 36) `func NewExpressionRaw(` - *NewExpressionRaw constructs an expression containing the given raw tokens.  There is no automatic validation that the given tokens produce a valid ...*
- `NewExpressionLiteral` (line 60) `func NewExpressionLiteral(` - *NewExpressionLiteral constructs an an expression that represents the given literal value.  Since an unknown value cannot be represented in source c...*
- `NewExpressionAbsTraversal` (line 69) `func NewExpressionAbsTraversal(` - *NewExpressionAbsTraversal constructs an expression that represents the given traversal, which must be absolute or this function will panic.*
- `Variables` (line 129) `func (e *Expression) Variables(` - *Variables returns the absolute traversals that exist within the receiving expression.*
- `RenameVariablePrefix` (line 150) `func (e *Expression) RenameVariablePrefix(` - *RenameVariablePrefix examines each of the absolute traversals in the receiving expression to see if they have the given sequence of names as a pref...*
- `newTraversal` (line 195) `func newTraversal(`
- `newTraverseName` (line 208) `func newTraverseName(`
- `newTraverseIndex` (line 220) `func newTraverseIndex(`

**Structs:**
- `Expression` (line 11)
- `Traversal` (line 189) - *Traversal represents a sequence of variable, attribute, and/or index operations.*
- `TraverseName` (line 202)
- `TraverseIndex` (line 214)

#### `ast_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/ast_test.go`

**Functions:**
- `makeTestTree` (line 15) `func makeTestTree(`

**Structs:**
- `TestTreeNode` (line 8)

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/doc.go`

*No symbols extracted*

#### `examples_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go`

**Functions:**
- `Example_generateFromScratch` (line 11) `func Example_generateFromScratch(`
- `ExampleExpression_RenameVariablePrefix` (line 74) `func ExampleExpression_RenameVariablePrefix(`

#### `format.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/format.go`

**Functions:**
- `format` (line 19) `func format(` - *format rewrites tokens within the given sequence, in-place, to adjust the whitespace around their content to achieve canonical formatting.*
- `formatIndent` (line 40) `func formatIndent(`
- `formatSpaces` (line 110) `func formatSpaces(`
- `formatCells` (line 158) `func formatCells(`
- `spaceAfterToken` (line 227) `func spaceAfterToken(` - *spaceAfterToken decides whether a particular subject token should have a space after it when surrounded by the given before and after tokens. "befo...*
- `linesForFormat` (line 342) `func linesForFormat(`
- `tokenIsNewline` (line 427) `func tokenIsNewline(`
- `tokenBracketChange` (line 440) `func tokenBracketChange(`

**Structs:**
- `formatLine` (line 463) - *formatLine represents a single line of source code for formatting purposes, splitting its tokens into up to three "cells":  lead: always present, r...*

#### `format_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/format_test.go`

**Functions:**
- `TestFormat` (line 13) `func TestFormat(`
- `TestLinesForFormat` (line 632) `func TestLinesForFormat(`

#### `fuzz.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go`

**Functions:**
- `Fuzz` (line 10) `func Fuzz(`

#### `generate.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/generate.go`

**Functions:**
- `TokensForValue` (line 23) `func TokensForValue(` - *TokensForValue returns a sequence of tokens that represents the given constant value.  This function only supports types that are used by HCL. In p...*
- `TokensForTraversal` (line 36) `func TokensForTraversal(` - *TokensForTraversal returns a sequence of tokens that represents the given traversal.  If the traversal is absolute then the result is a self-contai...*
- `appendTokensForValue` (line 42) `func appendTokensForValue(`
- `appendTokensForTraversal` (line 164) `func appendTokensForTraversal(`
- `appendTokensForTraversalStep` (line 171) `func appendTokensForTraversalStep(`
- `escapeQuotedStringLit` (line 207) `func escapeQuotedStringLit(`
- `appendRune` (line 248) `func appendRune(`

#### `generate_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go`

**Functions:**
- `TestTokensForValue` (line 14) `func TestTokensForValue(`
- `TestTokensForTraversal` (line 498) `func TestTokensForTraversal(`

#### `native_node_sorter.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go`

**Functions:**
- `Len` (line 11) `func (s nativeNodeSorter) Len(`
- `Less` (line 15) `func (s nativeNodeSorter) Less(`
- `Swap` (line 21) `func (s nativeNodeSorter) Swap(`

**Structs:**
- `nativeNodeSorter` (line 7)

#### `node.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/node.go`

**Functions:**
- `newNode` (line 17) `func newNode(`
- `Equal` (line 23) `func (n *node) Equal(`
- `BuildTokens` (line 27) `func (n *node) BuildTokens(`
- `Detach` (line 33) `func (n *node) Detach(` - *Detach removes the receiver from the list it currently belongs to. If the node is not currently in a list, this is a no-op.*
- `ReplaceWith` (line 60) `func (n *node) ReplaceWith(` - *ReplaceWith removes the receiver from the list it currently belongs to and inserts a new node with the given content in its place. If the node is n...*
- `assertUnattached` (line 83) `func (n *node) assertUnattached(`
- `BuildTokens` (line 100) `func (ns *nodes) BuildTokens(`
- `Clear` (line 107) `func (ns *nodes) Clear(`
- `Append` (line 112) `func (ns *nodes) Append(`
- `AppendNode` (line 121) `func (ns *nodes) AppendNode(`
- `Insert` (line 135) `func (ns *nodes) Insert(` - *Insert inserts a nodeContent at a given position. This is just a wrapper for InsertNode. See InsertNode for details.*
- `InsertNode` (line 147) `func (ns *nodes) InsertNode(` - *InsertNode inserts a node at a given position. The first argument is a node reference before which to insert. To insert it to an empty list, set po...*
- `AppendUnstructuredTokens` (line 163) `func (ns *nodes) AppendUnstructuredTokens(`
- `FindNodeWithContent` (line 176) `func (ns *nodes) FindNodeWithContent(` - *FindNodeWithContent searches the nodes for a node whose content equals the given content. If it finds one then it returns it. Otherwise it returns ...*
- `newNodeSet` (line 190) `func newNodeSet(`
- `Has` (line 194) `func (ns nodeSet) Has(`
- `Add` (line 202) `func (ns nodeSet) Add(`
- `Remove` (line 206) `func (ns nodeSet) Remove(`
- `Clear` (line 210) `func (ns nodeSet) Clear(`
- `List` (line 216) `func (ns nodeSet) List(`
- `FindNodeWithContent` (line 246) `func (ns nodeSet) FindNodeWithContent(` - *FindNodeWithContent searches the nodes for a node whose content equals the given content. If it finds one then it returns it. Otherwise it returns ...*
- `newInTree` (line 265) `func newInTree(`
- `assertUnattached` (line 271) `func (it *inTree) assertUnattached(`
- `walkChildNodes` (line 277) `func (it *inTree) walkChildNodes(`
- `BuildTokens` (line 283) `func (it *inTree) BuildTokens(`
- `walkChildNodes` (line 295) `func (n *leafNode) walkChildNodes(`

**Interfaces:**
- `nodeContent` (line 90) - *nodeContent is the interface type implemented by all AST content types.*

**Structs:**
- `node` (line 10) - *node represents a node in the AST.*
- `nodes` (line 96) - *nodes is a list of nodes.*
- `inTree` (line 260) - *inTree can be embedded into a content struct that has child nodes to get a standard implementation of the NodeContent interface and a record of a p...*
- `leafNode` (line 292) - *leafNode can be embedded into a content struct to give it a do-nothing implementation of walkChildNodes*

#### `parser.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/parser.go`

**Functions:**
- `parse` (line 29) `func parse(` - *up to AST nodes.  This strategy feels somewhat counter-intuitive, since most of the work the parser does is thrown away here, but this strategy is ...*
- `Partition` (line 74) `func (it inputTokens) Partition(`
- `PartitionType` (line 82) `func (it inputTokens) PartitionType(`
- `PartitionTypeOk` (line 91) `func (it inputTokens) PartitionTypeOk(`
- `PartitionTypeSingle` (line 101) `func (it inputTokens) PartitionTypeSingle(`
- `PartitionIncludingComments` (line 111) `func (it inputTokens) PartitionIncludingComments(` - *PartitionIncludeComments is like Partition except the returned "within" range includes any lead and line comments associated with the range.*
- `PartitionBlockItem` (line 128) `func (it inputTokens) PartitionBlockItem(` - *PartitionBlockItem is similar to PartitionIncludeComments but it returns the comments as separate token sequences so that they can be captured into...*
- `PartitionLeadComments` (line 135) `func (it inputTokens) PartitionLeadComments(`
- `PartitionLineEndTokens` (line 142) `func (it inputTokens) PartitionLineEndTokens(`
- `Slice` (line 150) `func (it inputTokens) Slice(`
- `Len` (line 162) `func (it inputTokens) Len(`
- `Tokens` (line 166) `func (it inputTokens) Tokens(`
- `Types` (line 170) `func (it inputTokens) Types(`
- `parseBody` (line 181) `func parseBody(` - *parseBody locates the given body within the given input tokens and returns the resulting *Body object as well as the tokens that appeared before an...*
- `parseBodyItem` (line 220) `func parseBodyItem(`
- `parseAttribute` (line 238) `func parseAttribute(`
- `parseBlock` (line 289) `func parseBlock(`
- `parseBlockLabels` (line 347) `func parseBlockLabels(`
- `parseExpression` (line 375) `func parseExpression(`
- `parseTraversal` (line 396) `func parseTraversal(`
- `parseTraversalStep` (line 413) `func parseTraversalStep(`
- `writerTokens` (line 482) `func writerTokens(` - *writerTokens takes a sequence of tokens as produced by the main hclsyntax package and transforms it into an equivalent sequence of tokens using thi...*
- `partitionTokens` (line 539) `func partitionTokens(` - *This works best when the range is aligned with token boundaries (e.g. because it was produced in terms of the scanner's result) but if that isn't t...*
- `partitionLeadCommentTokens` (line 577) `func partitionLeadCommentTokens(` - *partitionLeadCommentTokens takes a sequence of tokens that is assumed to immediately precede a construct that can have lead comment tokens, and ret...*
- `partitionLineEndTokens` (line 600) `func partitionLineEndTokens(` - *partitionLineEndTokens takes a sequence of tokens that is assumed to immediately follow a construct that can have a line comment, and returns first...*
- `lexConfig` (line 635) `func lexConfig(` - *lexConfig uses the hclsyntax scanner to get a token stream and then rewrites it into this package's token model.  Any errors produced during scanni...*

**Structs:**
- `inputTokens` (line 69)

#### `parser_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go`

**Functions:**
- `TestParse` (line 18) `func TestParse(`
- `TestPartitionTokens` (line 1232) `func TestPartitionTokens(`
- `TestPartitionLeadCommentTokens` (line 1382) `func TestPartitionLeadCommentTokens(`
- `TestLexConfig` (line 1458) `func TestLexConfig(`

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/public.go`

**Functions:**
- `NewFile` (line 11) `func NewFile(` - *NewFile creates a new file object that is empty and ready to have constructs added t it.*
- `ParseConfig` (line 26) `func ParseConfig(` - *ParseConfig interprets the given source bytes into a *hclwrite.File. The resulting AST can be used to perform surgical edits on the source code bef...*
- `Format` (line 38) `func Format(` - *Format takes source code and performs simple whitespace changes to transform it to a canonical layout style.  Format skips constructing an AST and ...*

#### `round_trip_test.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go`

**Functions:**
- `TestRoundTripVerbatim` (line 16) `func TestRoundTripVerbatim(`
- `TestRoundTripFormat` (line 82) `func TestRoundTripFormat(`

#### `tokens.go`
**Path:** `teamserver/pkg/profile/yaotl/hclwrite/tokens.go`

**Functions:**
- `asHCLSyntax` (line 33) `func (t *Token) asHCLSyntax(` - *asHCLSyntax returns the receiver expressed as an incomplete hclsyntax.Token. A complete token is not possible since we don't have source location i...*
- `Bytes` (line 46) `func (ts Tokens) Bytes(`
- `testValue` (line 52) `func (ts Tokens) testValue(`
- `Columns` (line 59) `func (ts Tokens) Columns(` - *Columns returns the number of columns (grapheme clusters) the token sequence occupies. The result is not meaningful if there are newline or single-...*
- `WriteTo` (line 72) `func (ts Tokens) WriteTo(` - *WriteTo takes an io.Writer and writes the bytes for each token to it, along with the spacing that separates each token. In other words, this allows...*
- `walkChildNodes` (line 109) `func (ts Tokens) walkChildNodes(`
- `BuildTokens` (line 113) `func (ts Tokens) BuildTokens(`
- `newIdentToken` (line 117) `func newIdentToken(`

**Structs:**
- `Token` (line 15) - *Token is a single sequence of bytes annotated with a type. It is similar in purpose to hclsyntax.Token, but discards the source position informatio...*

#### `ast.go`
**Path:** `teamserver/pkg/profile/yaotl/json/ast.go`

**Functions:**
- `Range` (line 21) `func (n *objectVal) Range(`
- `StartRange` (line 25) `func (n *objectVal) StartRange(`
- `Range` (line 35) `func (n *objectAttr) Range(`
- `StartRange` (line 39) `func (n *objectAttr) StartRange(`
- `Range` (line 49) `func (n *arrayVal) Range(`
- `StartRange` (line 53) `func (n *arrayVal) StartRange(`
- `Range` (line 62) `func (n *booleanVal) Range(`
- `StartRange` (line 66) `func (n *booleanVal) StartRange(`
- `Range` (line 75) `func (n *numberVal) Range(`
- `StartRange` (line 79) `func (n *numberVal) StartRange(`
- `Range` (line 88) `func (n *stringVal) Range(`
- `StartRange` (line 92) `func (n *stringVal) StartRange(`
- `Range` (line 100) `func (n *nullVal) Range(`
- `StartRange` (line 104) `func (n *nullVal) StartRange(`
- `Range` (line 115) `func (n invalidVal) Range(`
- `StartRange` (line 119) `func (n invalidVal) StartRange(`

**Interfaces:**
- `node` (line 9)

**Structs:**
- `objectVal` (line 14)
- `objectAttr` (line 29)
- `arrayVal` (line 43)
- `booleanVal` (line 57)
- `numberVal` (line 70)
- `stringVal` (line 83)
- `nullVal` (line 96)
- `invalidVal` (line 111) - *invalidVal is used as a placeholder where a value is needed for a valid parse tree but the input was invalid enough to prevent one from being created.*

#### `didyoumean.go`
**Path:** `teamserver/pkg/profile/yaotl/json/didyoumean.go`

**Functions:**
- `keywordSuggestion` (line 12) `func keywordSuggestion(` - *keywordSuggestion tries to find a valid JSON keyword that is close to the given string and returns it if found. If no keyword is close enough, retu...*
- `nameSuggestion` (line 25) `func nameSuggestion(` - *nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns it if found. If no suggesti...*

#### `didyoumean_test.go`
**Path:** `teamserver/pkg/profile/yaotl/json/didyoumean_test.go`

**Functions:**
- `TestKeywordSuggestion` (line 5) `func TestKeywordSuggestion(`

#### `doc.go`
**Path:** `teamserver/pkg/profile/yaotl/json/doc.go`

*No symbols extracted*

#### `fuzz.go`
**Path:** `teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go`

**Functions:**
- `Fuzz` (line 7) `func Fuzz(`

#### `navigation.go`
**Path:** `teamserver/pkg/profile/yaotl/json/navigation.go`

**Functions:**
- `ContextString` (line 13) `func (n navigation) ContextString(` - *Implementation of hcled.ContextString*
- `navigationStepsRev` (line 32) `func navigationStepsRev(`

**Structs:**
- `navigation` (line 8)

#### `navigation_test.go`
**Path:** `teamserver/pkg/profile/yaotl/json/navigation_test.go`

**Functions:**
- `TestNavigationContextString` (line 9) `func TestNavigationContextString(`

#### `parser.go`
**Path:** `teamserver/pkg/profile/yaotl/json/parser.go`

**Functions:**
- `parseFileContent` (line 11) `func parseFileContent(`
- `parseExpression` (line 26) `func parseExpression(`
- `parseValue` (line 41) `func parseValue(`
- `tokenCanStartValue` (line 101) `func tokenCanStartValue(`
- `parseObject` (line 110) `func parseObject(`
- `parseArray` (line 261) `func parseArray(`
- `parseNumber` (line 363) `func parseNumber(`
- `parseString` (line 406) `func parseString(`
- `parseKeyword` (line 461) `func parseKeyword(`

#### `parser_test.go`
**Path:** `teamserver/pkg/profile/yaotl/json/parser_test.go`

**Functions:**
- `init` (line 11) `func init(`
- `TestParse` (line 15) `func TestParse(`
- `TestParseWithPos` (line 619) `func TestParseWithPos(`
- `mustBigFloat` (line 661) `func mustBigFloat(`

#### `peeker.go`
**Path:** `teamserver/pkg/profile/yaotl/json/peeker.go`

**Functions:**
- `newPeeker` (line 8) `func newPeeker(`
- `Peek` (line 15) `func (p *peeker) Peek(`
- `Read` (line 19) `func (p *peeker) Read(`

**Structs:**
- `peeker` (line 3)

#### `public.go`
**Path:** `teamserver/pkg/profile/yaotl/json/public.go`

**Functions:**
- `Parse` (line 20) `func Parse(` - *Parse attempts to parse the given buffer as JSON and, if successful, returns a hcl.File for the HCL configuration represented by it.  This is not a...*
- `ParseWithStartPos` (line 29) `func ParseWithStartPos(` - *ParseWithStartPos attempts to parse like json.Parse, but unlike json.Parse you can pass a start position of the given JSON as a hcl.Pos.  In most c...*
- `ParseExpression` (line 76) `func ParseExpression(` - *ParseExpression parses the given buffer as a standalone JSON expression, returning it as an instance of Expression.*
- `ParseExpressionWithStartPos` (line 83) `func ParseExpressionWithStartPos(` - *ParseExpressionWithStartPos parses like json.ParseExpression, but unlike json.ParseExpression you can pass a start position of the given JSON expre...*
- `ParseFile` (line 92) `func ParseFile(` - *ParseFile is a convenience wrapper around Parse that first attempts to load data from the given filename, passing the result to Parse if successful...*

#### `public_test.go`
**Path:** `teamserver/pkg/profile/yaotl/json/public_test.go`

**Functions:**
- `TestParse_nonObject` (line 12) `func TestParse_nonObject(`
- `TestParseTemplate` (line 29) `func TestParseTemplate(`
- `TestParseTemplateUnwrap` (line 65) `func TestParseTemplateUnwrap(`
- `TestParse_malformed` (line 101) `func TestParse_malformed(`
- `TestParseWithStartPos` (line 117) `func TestParseWithStartPos(`
- `TestParseExpression` (line 187) `func TestParseExpression(`
- `TestParseExpression_malformed` (line 260) `func TestParseExpression_malformed(`
- `TestParseExpressionWithStartPos` (line 274) `func TestParseExpressionWithStartPos(`

#### `scanner.go`
**Path:** `teamserver/pkg/profile/yaotl/json/scanner.go`

**Functions:**
- `scan` (line 41) `func scan(` - *scan returns the primary tokens for the given JSON buffer in sequence.  The responsibility of this pass is to just mark the slices of the buffer as...*
- `byteCanStartNumber` (line 124) `func byteCanStartNumber(`
- `scanNumber` (line 138) `func scanNumber(`
- `byteCanStartKeyword` (line 157) `func byteCanStartKeyword(`
- `scanKeyword` (line 172) `func scanKeyword(`
- `scanString` (line 189) `func scanString(`
- `skipWhitespace` (line 241) `func skipWhitespace(`
- `Range` (line 280) `func (p *pos) Range(`
- `posRange` (line 292) `func posRange(`
- `GoString` (line 300) `func (t token) GoString(`
- `isAlphabetical` (line 304) `func isAlphabetical(`

**Structs:**
- `token` (line 28)
- `pos` (line 275)

#### `scanner_test.go`
**Path:** `teamserver/pkg/profile/yaotl/json/scanner_test.go`

**Functions:**
- `TestScan` (line 12) `func TestScan(`

#### `structure.go`
**Path:** `teamserver/pkg/profile/yaotl/json/structure.go`

**Functions:**
- `Content` (line 29) `func (b *body) Content(`
- `PartialContent` (line 77) `func (b *body) PartialContent(`
- `JustAttributes` (line 169) `func (b *body) JustAttributes(` - *JustAttributes for JSON bodies interprets all properties of the wrapped JSON object as attributes and returns them.*
- `MissingItemRange` (line 219) `func (b *body) MissingItemRange(`
- `unpackBlock` (line 232) `func (b *body) unpackBlock(`
- `collectDeepAttrs` (line 325) `func (b *body) collectDeepAttrs(` - *collectDeepAttrs takes either a single object or an array of objects and flattens it into a list of object attributes, collecting attributes from a...*
- `Value` (line 381) `func (e *expression) Value(`
- `Variables` (line 513) `func (e *expression) Variables(`
- `Range` (line 557) `func (e *expression) Range(`
- `StartRange` (line 561) `func (e *expression) StartRange(`
- `AsTraversal` (line 566) `func (e *expression) AsTraversal(` - *Implementation for hcl.AbsTraversalForExpr.*
- `ExprCall` (line 583) `func (e *expression) ExprCall(` - *Implementation for hcl.ExprCall.*
- `ExprList` (line 606) `func (e *expression) ExprList(` - *Implementation for hcl.ExprList.*
- `ExprMap` (line 620) `func (e *expression) ExprMap(` - *Implementation for hcl.ExprMap.*

**Structs:**
- `body` (line 14) - *body is the implementation of "Body" used for files processed with the JSON parser.*
- `expression` (line 25) - *expression is the implementation of "Expression" used for files processed with the JSON parser.*

#### `structure_test.go`
**Path:** `teamserver/pkg/profile/yaotl/json/structure_test.go`

**Functions:**
- `TestBodyPartialContent` (line 15) `func TestBodyPartialContent(`
- `TestBodyContent` (line 1080) `func TestBodyContent(`
- `TestJustAttributes` (line 1139) `func TestJustAttributes(`
- `TestExpressionVariables` (line 1237) `func TestExpressionVariables(`
- `TestExpressionAsTraversal` (line 1326) `func TestExpressionAsTraversal(`
- `TestStaticExpressionList` (line 1338) `func TestStaticExpressionList(`
- `TestExpression_Value` (line 1357) `func TestExpression_Value(`
- `TestExpressionValue_Diags` (line 1418) `func TestExpressionValue_Diags(` - *TestExpressionValue_Diags asserts that Value() returns diagnostics from nested evaluations for complex objects (e.g. ObjectVal, ArrayVal)*

#### `tokentype_string.go`
**Path:** `teamserver/pkg/profile/yaotl/json/tokentype_string.go`

**Functions:**
- `String` (line 24) `func (i tokenType) String(`

#### `merged.go`
**Path:** `teamserver/pkg/profile/yaotl/merged.go`

**Functions:**
- `MergeFiles` (line 15) `func MergeFiles(` - *MergeFiles combines the given files to produce a single body that contains configuration from all of the given files.  The ordering of the given fi...*
- `MergeBodies` (line 25) `func MergeBodies(` - *MergeBodies is like MergeFiles except it deals directly with bodies, rather than with entire files.*
- `EmptyBody` (line 71) `func EmptyBody(` - *EmptyBody returns a body with no content. This body can be used as a placeholder when a body is required but no body content is available.*
- `Content` (line 85) `func (mb mergedBodies) Content(` - *Content returns the content produced by applying the given schema to all of the merged bodies and merging the result.  Although required attributes...*
- `PartialContent` (line 92) `func (mb mergedBodies) PartialContent(`
- `JustAttributes` (line 96) `func (mb mergedBodies) JustAttributes(`
- `MissingItemRange` (line 130) `func (mb mergedBodies) MissingItemRange(`
- `mergedContent` (line 142) `func (mb mergedBodies) mergedContent(`

#### `ops.go`
**Path:** `teamserver/pkg/profile/yaotl/ops.go`

**Functions:**
- `Index` (line 23) `func Index(` - *Index is a helper function that performs the same operation as the index operator in the HCL expression language. That is, the result is the same a...*
- `GetAttr` (line 262) `func GetAttr(` - *GetAttr is a helper function that performs the same operation as the attribute access in the HCL expression language. That is, the result is the sa...*
- `ApplyPath` (line 404) `func ApplyPath(` - *ApplyPath is a helper function that applies a cty.Path to a value using the indexing and attribute access operations from HCL.  This is similar to ...*

#### `pos.go`
**Path:** `teamserver/pkg/profile/yaotl/pos.go`

**Functions:**
- `RangeBetween` (line 58) `func RangeBetween(` - *RangeBetween returns a new range that spans from the beginning of the start range to the end of the end range.  The result is meaningless if the tw...*
- `RangeOver` (line 74) `func RangeOver(` - *RangeOver returns a new range that covers both of the given ranges and possibly additional content between them if the two ranges do not overlap.  ...*
- `ContainsPos` (line 106) `func (r Range) ContainsPos(` - *ContainsPos returns true if and only if the given position is contained within the receiving range.  In the unlikely case that the line/column info...*
- `ContainsOffset` (line 112) `func (r Range) ContainsOffset(` - *ContainsOffset returns true if and only if the given byte offset is within the receiving Range.*
- `Ptr` (line 120) `func (r Range) Ptr(` - *Ptr returns a pointer to a copy of the receiver. This is a convenience when ranges in places where pointers are required, such as in Diagnostic, bu...*
- `String` (line 127) `func (r Range) String(` - *String returns a compact string representation of the receiver. Callers should generally prefer to present a range more visually, e.g. via markers ...*
- `Empty` (line 145) `func (r Range) Empty(`
- `CanSliceBytes` (line 155) `func (r Range) CanSliceBytes(` - *CanSliceBytes returns true if SliceBytes could return an accurate sub-slice of the given slice.  This effectively tests whether the start and end o...*
- `SliceBytes` (line 176) `func (r Range) SliceBytes(` - *SliceBytes returns a sub-slice of the given slice that is covered by the receiving range, assuming that the given slice is the source code of the f...*
- `Overlaps` (line 197) `func (r Range) Overlaps(` - *Overlaps returns true if the receiver and the other given range share any characters in common.*
- `Overlap` (line 219) `func (r Range) Overlap(` - *Overlap finds a range that is either identical to or a sub-range of both the receiver and the other given range. It returns an empty range within t...*
- `PartitionAround` (line 257) `func (r Range) PartitionAround(` - *PartitionAround finds the portion of the given range that overlaps with the receiver and returns three ranges: the portion of the receiver that pre...*

**Structs:**
- `Pos` (line 10) - *Pos represents a single position in a source file, by addressing the start byte of a unicode character encoded in UTF-8.  Pos is generally used onl...*
- `Range` (line 43) - *Range represents a span of characters between two positions in a source file.  This struct is usually used by value in types that represent AST nod...*

#### `pos_scanner.go`
**Path:** `teamserver/pkg/profile/yaotl/pos_scanner.go`

**Functions:**
- `NewRangeScanner` (line 41) `func NewRangeScanner(` - *NewRangeScanner creates a new RangeScanner for the given buffer, producing ranges for the given filename.  Since ranges have grapheme-cluster granu...*
- `NewRangeScannerFragment` (line 49) `func NewRangeScannerFragment(` - *NewRangeScannerFragment is like NewRangeScanner but the ranges it produces will be offset by the given starting position, which is appropriate for ...*
- `Scan` (line 58) `func (sc *RangeScanner) Scan(`
- `Range` (line 138) `func (sc *RangeScanner) Range(` - *Range returns a range that covers the latest token obtained after a call to Scan returns true.*
- `Bytes` (line 144) `func (sc *RangeScanner) Bytes(` - *Bytes returns the slice of the input buffer that is covered by the range that would be returned by Range.*
- `Err` (line 150) `func (sc *RangeScanner) Err(` - *Err can be called after Scan returns false to determine if the latest read resulted in an error, and obtain that error if so.*

**Structs:**
- `RangeScanner` (line 21) - *RangeScanner is a helper that will scan over a buffer using a bufio.SplitFunc and visit a source range for each token matched.  For example, this c...*

#### `schema.go`
**Path:** `teamserver/pkg/profile/yaotl/schema.go`

**Structs:**
- `BlockHeaderSchema` (line 5) - *BlockHeaderSchema represents the shape of a block header, and is used for matching blocks within bodies.*
- `AttributeSchema` (line 12) - *AttributeSchema represents the requirements for an attribute, and is used for matching attributes within bodies.*
- `BodySchema` (line 18) - *BodySchema represents the desired shallow structure of a body.*

#### `spec_test.go`
**Path:** `teamserver/pkg/profile/yaotl/specsuite/spec_test.go`

**Functions:**
- `TestMain` (line 15) `func TestMain(`
- `build` (line 30) `func build(`
- `TestSpec` (line 44) `func TestSpec(`
- `goBuild` (line 91) `func goBuild(`

#### `static_expr.go`
**Path:** `teamserver/pkg/profile/yaotl/static_expr.go`

**Functions:**
- `StaticExpr` (line 22) `func StaticExpr(` - *StaticExpr returns an Expression that always evaluates to the given value.  This is useful to substitute default values for expressions that are no...*
- `Value` (line 26) `func (e staticExpr) Value(`
- `Variables` (line 30) `func (e staticExpr) Variables(`
- `Range` (line 34) `func (e staticExpr) Range(`
- `StartRange` (line 38) `func (e staticExpr) StartRange(`

**Structs:**
- `staticExpr` (line 7)

#### `structure.go`
**Path:** `teamserver/pkg/profile/yaotl/structure.go`

**Functions:**
- `OfType` (line 129) `func (els Blocks) OfType(` - *OfType filters the receiving block sequence by block type name, returning a new block sequence including only the blocks of the requested type.*
- `ByType` (line 141) `func (els Blocks) ByType(` - *ByType transforms the receiving block sequence into a map from type name to block sequences of only that type.*

**Interfaces:**
- `Body` (line 41) - *Body is a container for attributes and blocks. It serves as the primary unit of hierarchical structure within configuration.  The content of a body...*
- `Expression` (line 95) - *Expression is a literal value or an expression provided in the configuration, which can be evaluated within a scope to produce a value.*

**Structs:**
- `File` (line 8) - *File is the top-level node that results from parsing a HCL file.*
- `Block` (line 19) - *Block represents a nested block within a Body.*
- `BodyContent` (line 77) - *BodyContent is the result of applying a BodySchema to a Body.*
- `Attribute` (line 85) - *Attribute represents an attribute from within a body.*

#### `structure_at_pos.go`
**Path:** `teamserver/pkg/profile/yaotl/structure_at_pos.go`

**Functions:**
- `BlocksAtPos` (line 25) `func (f *File) BlocksAtPos(` - *BlocksAtPos attempts to find all of the blocks that contain the given position, ordered so that the outermost block is first and the innermost bloc...*
- `OutermostBlockAtPos` (line 44) `func (f *File) OutermostBlockAtPos(` - *OutermostBlockAtPos attempts to find a top-level block in the receiving file that contains the given position. This is a best-effort method that ma...*
- `InnermostBlockAtPos` (line 64) `func (f *File) InnermostBlockAtPos(` - *InnermostBlockAtPos attempts to find the most deeply-nested block in the receiving file that contains the given position. This is a best-effort met...*
- `OutermostExprAtPos` (line 86) `func (f *File) OutermostExprAtPos(` - *OutermostExprAtPos attempts to find an expression in the receiving file that contains the given position. This is a best-effort method that may not...*
- `AttributeAtPos` (line 105) `func (f *File) AttributeAtPos(` - *AttributeAtPos attempts to find an attribute definition in the receiving file that contains the given position. This is a best-effort method that m...*

#### `traversal.go`
**Path:** `teamserver/pkg/profile/yaotl/traversal.go`

**Functions:**
- `TraversalJoin` (line 24) `func TraversalJoin(` - *TraversalJoin appends a relative traversal to an absolute traversal to produce a new absolute traversal.*
- `TraverseRel` (line 41) `func (t Traversal) TraverseRel(` - *TraverseRel applies the receiving traversal to the given value, returning the resulting value. This is supported only for relative traversals, and ...*
- `TraverseAbs` (line 62) `func (t Traversal) TraverseAbs(` - *TraverseAbs applies the receiving traversal to the given eval context, returning the resulting value. This is supported only for absolute traversal...*
- `IsRelative` (line 122) `func (t Traversal) IsRelative(` - *IsRelative returns true if the receiver is a relative traversal, or false otherwise.*
- `SimpleSplit` (line 139) `func (t Traversal) SimpleSplit(` - *SimpleSplit returns a TraversalSplit where the name lookup is the absolute part and the remainder is the relative part. Supported only for absolute...*
- `RootName` (line 151) `func (t Traversal) RootName(` - *RootName returns the root name for a absolute traversal. Will panic if called on a relative traversal.*
- `SourceRange` (line 160) `func (t Traversal) SourceRange(` - *SourceRange returns the source range for the traversal.*
- `TraverseAbs` (line 184) `func (t TraversalSplit) TraverseAbs(` - *TraverseAbs traverses from a scope to the value resulting from the absolute traversal.*
- `TraverseRel` (line 190) `func (t TraversalSplit) TraverseRel(` - *TraverseRel traverses from a given value, assumed to be the result of TraverseAbs on some scope, to a final result for the entire split traversal.*
- `Traverse` (line 196) `func (t TraversalSplit) Traverse(` - *Traverse is a convenience function to apply TraverseAbs followed by TraverseRel.*
- `Join` (line 208) `func (t TraversalSplit) Join(` - *Join concatenates together the Abs and Rel parts to produce a single absolute traversal.*
- `RootName` (line 213) `func (t TraversalSplit) RootName(` - *RootName returns the root name for the absolute part of the split.*
- `isTraverserSigil` (line 228) `func (tr isTraverser) isTraverserSigil(`
- `TraversalStep` (line 242) `func (tn TraverseRoot) TraversalStep(` - *TraversalStep on a TraverseName immediately panics, because absolute traversals cannot be directly traversed.*
- `SourceRange` (line 246) `func (tn TraverseRoot) SourceRange(`
- `TraversalStep` (line 257) `func (tn TraverseAttr) TraversalStep(`
- `SourceRange` (line 261) `func (tn TraverseAttr) SourceRange(`
- `TraversalStep` (line 272) `func (tn TraverseIndex) TraversalStep(`
- `SourceRange` (line 276) `func (tn TraverseIndex) SourceRange(`
- `TraversalStep` (line 287) `func (tn TraverseSplat) TraversalStep(`
- `SourceRange` (line 291) `func (tn TraverseSplat) SourceRange(`

**Interfaces:**
- `Traverser` (line 218) - *A Traverser is a step within a Traversal.*

**Structs:**
- `TraversalSplit` (line 177) - *TraversalSplit represents a pair of traversals, the first of which is an absolute traversal and the second of which is relative to the first.  This...*
- `isTraverser` (line 225) - *Embed this in a struct to declare it as a Traverser*
- `TraverseRoot` (line 234) - *TraverseRoot looks up a root name in a scope. It is used as the first step of an absolute Traversal, and cannot itself be traversed directly.*
- `TraverseAttr` (line 251) - *TraverseAttr looks up an attribute in its initial value.*
- `TraverseIndex` (line 266) - *TraverseIndex applies the index operation to its initial value.*
- `TraverseSplat` (line 281) - *TraverseSplat applies the splat operation to its initial value.*

#### `traversal_for_expr.go`
**Path:** `teamserver/pkg/profile/yaotl/traversal_for_expr.go`

**Functions:**
- `AbsTraversalForExpr` (line 20) `func AbsTraversalForExpr(` - *A particular Expression implementation can support this function by offering a method called AsTraversal that takes no arguments and returns either...*
- `RelTraversalForExpr` (line 52) `func RelTraversalForExpr(` - *RelTraversalForExpr is similar to AbsTraversalForExpr but it returns a relative traversal instead. Due to the nature of HCL expressions, the first ...*
- `ExprAsKeyword` (line 108) `func ExprAsKeyword(` - *The above approach will generate the same message for both the use of an unrecognized keyword and for not using a keyword at all, which is usually ...*

#### `agent.go`
**Path:** `teamserver/pkg/service/agent.go`

**Functions:**
- `NewAgentService` (line 45) `func NewAgentService(`
- `Json` (line 58) `func (a *AgentService) Json(`
- `SendTask` (line 67) `func (a *AgentService) SendTask(`
- `SendResponse` (line 87) `func (a *AgentService) SendResponse(`
- `SendAgentBuildRequest` (line 140) `func (a *AgentService) SendAgentBuildRequest(`

**Structs:**
- `CommandParam` (line 13)
- `Command` (line 19)
- `AgentService` (line 28)

#### `external.go`
**Path:** `teamserver/pkg/service/external.go`

*No symbols extracted*

#### `listener.go`
**Path:** `teamserver/pkg/service/listener.go`

**Functions:**
- `Start` (line 17) `func (l *ListenerService) Start(`
- `Json` (line 37) `func (l *ListenerService) Json(`

**Structs:**
- `ListenerService` (line 8)

#### `service.go`
**Path:** `teamserver/pkg/service/service.go`

**Functions:**
- `NewService` (line 27) `func NewService(`
- `Start` (line 35) `func (s *Service) Start(`
- `handleConnection` (line 50) `func (s *Service) handleConnection(`
- `authenticate` (line 75) `func (s *Service) authenticate(`
- `routine` (line 144) `func (s *Service) routine(` - *the main service routine*
- `dispatch` (line 166) `func (s *Service) dispatch(`
- `AgentExist` (line 703) `func (s *Service) AgentExist(`
- `ClientClose` (line 713) `func (s *Service) ClientClose(`
- `ListenerExist` (line 763) `func (s *Service) ListenerExist(`
- `ListenerAdd` (line 775) `func (s *Service) ListenerAdd(`

#### `types.go`
**Path:** `teamserver/pkg/service/types.go`

**Functions:**
- `WriteJson` (line 69) `func (c *ClientService) WriteJson(`

**Interfaces:**
- `Teamserver` (line 19)

**Structs:**
- `ClientService` (line 13)
- `ConfigService` (line 30)
- `Service` (line 36)

#### `socks.go`
**Path:** `teamserver/pkg/socks/socks.go`

**Functions:**
- `NewSocks` (line 17) `func NewSocks(`
- `SetHandler` (line 29) `func (s *Socks) SetHandler(`
- `Start` (line 35) `func (s *Socks) Start(`
- `Close` (line 62) `func (s *Socks) Close(`

**Structs:**
- `Socks` (line 9)

#### `util.go`
**Path:** `teamserver/pkg/socks/util.go`

**Functions:**
- `SubNegotiationClient` (line 70) `func SubNegotiationClient(`
- `ReadSocksHeader` (line 114) `func ReadSocksHeader(`
- `CreateResponsePackage` (line 239) `func CreateResponsePackage(`
- `SendConnectSuccess` (line 255) `func SendConnectSuccess(`
- `SendAddressTypeNotSupported` (line 260) `func SendAddressTypeNotSupported(`
- `SendCommandNotSupported` (line 265) `func SendCommandNotSupported(`
- `SendConnectFailure` (line 270) `func SendConnectFailure(`

**Structs:**
- `SocksHeader` (line 55)
- `NegotiationHeader` (line 64)

#### `utils.go`
**Path:** `teamserver/pkg/utils/utils.go`

**Functions:**
- `UTF16BytesToString` (line 25) `func UTF16BytesToString(`
- `GenerateID` (line 34) `func GenerateID(`
- `GenerateString` (line 53) `func GenerateString(`
- `EncodeCommand` (line 65) `func EncodeCommand(`
- `IP2Inet` (line 70) `func IP2Inet(`
- `Port2Htons` (line 84) `func Port2Htons(`
- `ByteCountSI` (line 90) `func ByteCountSI(`
- `GetTeamserverPath` (line 104) `func GetTeamserverPath(`
- `IntToHexString` (line 131) `func IntToHexString(`
- `HexIntToString` (line 135) `func HexIntToString(`
- `HexIntToBigEndian` (line 141) `func HexIntToBigEndian(`

#### `discord.go`
**Path:** `teamserver/pkg/webhook/discord.go`

**Structs:**
- `Message` (line 3)
- `Embed` (line 10)
- `Author` (line 22)
- `Field` (line 28)
- `Thumbnail` (line 34)
- `Image` (line 38)
- `Footer` (line 42)

#### `webhook.go`
**Path:** `teamserver/pkg/webhook/webhook.go`

**Functions:**
- `StringPtr` (line 20) `func StringPtr(`
- `BoolPtr` (line 24) `func BoolPtr(`
- `NewWebHook` (line 28) `func NewWebHook(`
- `NewAgent` (line 32) `func (w *WebHook) NewAgent(`
- `SetDiscord` (line 134) `func (w *WebHook) SetDiscord(`

**Structs:**
- `WebHook` (line 12)

#### `types.go`
**Path:** `teamserver/pkg/win32/types.go`

**Functions:**
- `StatusToString` (line 78) `func StatusToString(`

### H (54 files)

#### `External.h`
**Path:** `client/include/External.h`

**Macros:**
- `HAVOC_EXTERNAL_H` (line 2)

#### `DemonCmdDispatch.h`
**Path:** `client/include/Havoc/DemonCmdDispatch.h`

**Classes:**
- `Commands` (line 23)
- `DispatchOutput` (line 53)
- `CommandExecute` (line 61)

**Macros:**
- `HAVOC_DEMONCMDDISPATCH_H` (line 2)
- `SEND` (line 11)
- `CONSOLE_ERROR` (line 14)
- `CONSOLE_INFO` (line 19)

**Structs:**
- `SubCommand` (line 118)
- `Command` (line 130)

#### `Event.h`
**Path:** `client/include/Havoc/PythonApi/Event.h`

**Macros:**
- `HAVOC_EVENT_H` (line 2)

#### `HavocUi.h`
**Path:** `client/include/Havoc/PythonApi/HavocUi.h`

**Macros:**
- `HAVOC_HAVOCUI_H` (line 2)

#### `PyDemonClass.h`
**Path:** `client/include/Havoc/PythonApi/PyDemonClass.h`

**Macros:**
- `HAVOC_PYDEMONCLASS_H` (line 2)

#### `PythonApi.h`
**Path:** `client/include/Havoc/PythonApi/PythonApi.h`

**Macros:**
- `HAVOC_PYTHONAPI_H` (line 2)
- `PY_FUNCTION` (line 9)
- `PY_FUNCTION_KW` (line 11)

**Structs:**
- `Stdout` (line 70)

#### `DemonInteracted.h`
**Path:** `client/include/UserInterface/Widgets/DemonInteracted.h`

**Classes:**
- `DemonInteracted` (line 9)
- `DemonInput` (line 26)

**Macros:**
- `HAVOC_DEMONINTERACTED_H` (line 2)

#### `LootWidget.h`
**Path:** `client/include/UserInterface/Widgets/LootWidget.h`

**Classes:**
- `ImageLabel` (line 15)
- `LootWidget` (line 39)

**Macros:**
- `HAVOC_LOOTWIDGET_H` (line 2)

#### `ScriptManager.h`
**Path:** `client/include/UserInterface/Widgets/ScriptManager.h`

**Macros:**
- `SCRIPTMANAGERVVJSUY_H` (line 2)

#### `TeamserverTabSession.h`
**Path:** `client/include/UserInterface/Widgets/TeamserverTabSession.h`

**Macros:**
- `HAVOC_TEAMSERVERTABSESSION_H` (line 2)

#### `Base64.h`
**Path:** `client/include/Util/Base64.h`

**Macros:**
- `HAVOC_BASE64_H` (line 2)

#### `ColorText.h`
**Path:** `client/include/Util/ColorText.h`

**Macros:**
- `HAVOC_COLORTEXT_H` (line 2)

**Structs:**
- `Colors` (line 8)
- `Hex` (line 9)

#### `Demon.h`
**Path:** `payloads/Demon/include/Demon.h`

**Macros:**
- `DEMON_DEMON_H` (line 2)

**Structs:**
- `_CONFIG` (line 121)

#### `Clr.h`
**Path:** `payloads/Demon/include/common/Clr.h`

**Macros:**
- `DEMON_CLR_H` (line 2)
- `DUMMY_METHOD` (line 53)
- `DUMMY_METHOD` (line 88)
- `DUMMY_METHOD` (line 186)
- `DUMMY_METHOD` (line 291)
- `DUMMY_METHOD` (line 586)
- `DEMOn_CLR_ERROR_REFUSE_VERSION` (line 708)

**Structs:**
- `_BinderVtbl` (line 55)
- `_Binder` (line 83)
- `_AppDomainVtbl` (line 90)
- `_AppDomain` (line 181)
- `_AssemblyVtbl` (line 188)
- `_Assembly` (line 286)
- `_TypeVtbl` (line 293)
- `ICLRRuntimeInfoVtbl` (line 433)
- `_ICLRRuntimeInfo` (line 517)
- `_Type` (line 521)
- `ICLRMetaHostVtbl` (line 525)
- `_ICLRMetaHost` (line 579)
- `_MethodInfoVtbl` (line 588)
- `_MethodInfo` (line 656)
- `_DOTNET_ARGS` (line 660)

#### `Defines.h`
**Path:** `payloads/Demon/include/common/Defines.h`

**Macros:**
- `DEMON_STRINGS_H` (line 2)
- `PROCESS_ARCH_UNKNOWN` (line 3)
- `PROCESS_ARCH_X86` (line 5)
- `PROCESS_ARCH_X64` (line 6)
- `PROCESS_ARCH_IA64` (line 7)
- `PROCESS_AGENT_ARCH` (line 10)
- `PROCESS_AGENT_ARCH` (line 12)
- `DEMON_MAGIC_VALUE` (line 14)
- `WIN_VERSION_UNKNOWN` (line 16)
- `WIN_VERSION_XP` (line 18)
- `WIN_VERSION_VISTA` (line 19)
- `WIN_VERSION_2008` (line 20)
- `WIN_VERSION_7` (line 21)
- `WIN_VERSION_2008_R2` (line 22)
- `WIN_VERSION_2008_R2` (line 23)
- `WIN_VERSION_2012` (line 24)
- `WIN_VERSION_8` (line 25)
- `WIN_VERSION_8_1` (line 26)
- `WIN_VERSION_2012_R2` (line 27)
- `WIN_VERSION_10` (line 28)
- `WIN_VERSION_2016_X` (line 29)
- `LDR_GADGET_MODULE_SIZE` (line 30)
- `LDR_GADGET_HEADER_SIZE` (line 32)
- `PROXYLOAD_NONE` (line 33)
- `PROXYLOAD_RTLREGISTERWAIT` (line 35)
- `PROXYLOAD_RTLCREATETIMER` (line 36)
- `PROXYLOAD_RTLQUEUEWORKITEM` (line 37)
- `AMSIETW_PATCH_NONE` (line 38)
- `AMSIETW_PATCH_HWBP` (line 40)
- `AMSIETW_PATCH_MEMORY` (line 41)
- `H_FUNC_LDRLOADDLL` (line 44)
- `H_FUNC_LDRGETPROCEDUREADDRESS` (line 45)
- `H_FUNC_NTADDBOOTENTRY` (line 46)
- `H_FUNC_NTALLOCATEVIRTUALMEMORY` (line 47)
- `H_FUNC_NTFREEVIRTUALMEMORY` (line 48)
- `H_FUNC_NTUNMAPVIEWOFSECTION` (line 49)
- `H_FUNC_NTWRITEVIRTUALMEMORY` (line 50)
- `H_FUNC_NTSETINFORMATIONVIRTUALMEMORY` (line 51)
- `H_FUNC_NTQUERYVIRTUALMEMORY` (line 52)
- `H_FUNC_NTOPENPROCESSTOKEN` (line 53)
- `H_FUNC_NTOPENTHREADTOKEN` (line 54)
- `H_FUNC_NTQUERYOBJECT` (line 55)
- `H_FUNC_NTTRACEEVENT` (line 56)
- `H_FUNC_NTOPENPROCESS` (line 57)
- `H_FUNC_NTTERMINATEPROCESS` (line 58)
- `H_FUNC_NTOPENTHREAD` (line 59)
- `H_FUNC_NTOPENTHREADTOKEN` (line 60)
- `H_FUNC_NTSETCONTEXTTHREAD` (line 61)
- `H_FUNC_NTGETCONTEXTTHREAD` (line 62)
- `H_FUNC_NTCLOSE` (line 63)
- `H_FUNC_NTCONTINUE` (line 64)
- `H_FUNC_NTSETEVENT` (line 65)
- `H_FUNC_NTCREATEEVENT` (line 66)
- `H_FUNC_NTWAITFORSINGLEOBJECT` (line 67)
- `H_FUNC_NTSIGNALANDWAITFORSINGLEOBJECT` (line 68)
- `H_FUNC_NTGETNEXTTHREAD` (line 69)
- `H_FUNC_NTRESUMETHREAD` (line 70)
- `H_FUNC_NTSUSPENDTHREAD` (line 71)
- `H_FUNC_NTDUPLICATEOBJECT` (line 72)
- `H_FUNC_NTQUERYINFORMATIONTHREAD` (line 73)
- `H_FUNC_NTCREATETHREADEX` (line 74)
- `H_FUNC_NTQUEUEAPCTHREAD` (line 75)
- `H_FUNC_NTQUERYSYSTEMINFORMATION` (line 76)
- `H_FUNC_NTQUERYINFORMATIONTOKEN` (line 77)
- `H_FUNC_NTQUERYINFORMATIONPROCESS` (line 78)
- `H_FUNC_NTSETINFORMATIONTHREAD` (line 79)
- `H_FUNC_NTSETINFORMATIONVIRTUALMEMORY` (line 80)
- `H_FUNC_NTPROTECTVIRTUALMEMORY` (line 81)
- `H_FUNC_NTREADVIRTUALMEMORY` (line 82)
- `H_FUNC_NTFREEVIRTUALMEMORY` (line 83)
- `H_FUNC_NTTERMINATETHREAD` (line 84)
- `H_FUNC_NTWRITEVIRTUALMEMORY` (line 85)
- `H_FUNC_NTDUPLICATETOKEN` (line 86)
- `H_FUNC_NTALERTRESUMETHREAD` (line 87)
- `H_FUNC_NTTESTALERT` (line 88)
- `H_FUNC_RTLALLOCATEHEAP` (line 89)
- `H_FUNC_RTLREALLOCATEHEAP` (line 90)
- `H_FUNC_RTLFREEHEAP` (line 91)
- `H_FUNC_RTLEXITUSERPROCESS` (line 92)
- `H_FUNC_RTLRANDOMEX` (line 93)
- `H_FUNC_RTLRANDOMEX` (line 94)
- `H_FUNC_RTLNTSTATUSTODOSERROR` (line 95)
- `H_FUNC_RTLGETVERSION` (line 96)
- `H_FUNC_RTLADDVECTOREDEXCEPTIONHANDLER` (line 97)
- `H_FUNC_RTLREMOVEVECTOREDEXCEPTIONHANDLER` (line 98)
- `H_FUNC_RTLCREATETIMERQUEUE` (line 99)
- `H_FUNC_RTLDELETETIMERQUEUE` (line 100)
- `H_FUNC_RTLCREATETIMER` (line 101)
- `H_FUNC_RTLQUEUEWORKITEM` (line 102)
- `H_FUNC_RTLREGISTERWAIT` (line 103)
- `H_FUNC_RTLCAPTURECONTEXT` (line 104)
- `H_FUNC_RTLCOPYMAPPEDMEMORY` (line 105)
- `H_FUNC_RTLFILLMEMORY` (line 106)
- `H_FUNC_RTLEXITUSERTHREAD` (line 107)
- `H_FUNC_RTLSUBAUTHORITYSID` (line 108)
- `H_FUNC_RTLSUBAUTHORITYCOUNTSID` (line 109)
- `H_FUNC_LOADLIBRARYW` (line 110)
- `H_FUNC_GETCOMPUTERNAMEEXA` (line 112)
- `H_FUNC_WAITFORSINGLEOBJECTEX` (line 113)
- `H_FUNC_VIRTUALPROTECT` (line 114)
- `H_FUNC_GETMODULEHANDLEA` (line 115)
- `H_FUNC_GETPROCADDRESS` (line 116)
- `H_FUNC_GETCURRENTDIRECTORYW` (line 117)
- `H_FUNC_FINDFIRSTFILEW` (line 118)
- `H_FUNC_FINDNEXTFILEW` (line 119)
- `H_FUNC_FINDCLOSE` (line 120)
- `H_FUNC_FILETIMETOSYSTEMTIME` (line 121)
- `H_FUNC_SYSTEMTIMETOTZSPECIFICLOCALTIME` (line 122)
- `H_FUNC_OUTPUTDEBUGSTRINGA` (line 123)
- `H_FUNC_DEBUGBREAK` (line 124)
- `H_FUNC_SYSTEMFUNCTION032` (line 125)
- `H_FUNC_LOOKUPACCOUNTSIDW` (line 126)
- `H_FUNC_LOGONUSEREXW` (line 127)
- `H_FUNC_VSNPRINTF` (line 128)
- `H_FUNC_GETADAPTERSINFO` (line 129)
- `H_FUNC_WINHTTPOPEN` (line 130)
- `H_FUNC_WINHTTPCONNECT` (line 131)
- `H_FUNC_WINHTTPOPENREQUEST` (line 132)
- `H_FUNC_WINHTTPSETOPTION` (line 133)
- `H_FUNC_WINHTTPSENDREQUEST` (line 134)
- `H_FUNC_WINHTTPRECEIVERESPONSE` (line 135)
- `H_FUNC_WINHTTPADDREQUESTHEADERS` (line 136)
- `H_FUNC_WINHTTPREADDATA` (line 137)
- `H_FUNC_WINHTTPQUERYHEADERS` (line 138)
- `H_FUNC_WINHTTPCLOSEHANDLE` (line 139)
- `H_FUNC_WINHTTPGETIEPROXYCONFIGFORCURRENTUSER` (line 140)
- `H_FUNC_WINHTTPGETPROXYFORURL` (line 141)
- `H_FUNC_VIRTUALPROTECTEX` (line 142)
- `H_FUNC_LOCALALLOC` (line 143)
- `H_FUNC_LOCALREALLOC` (line 144)
- `H_FUNC_LOCALFREE` (line 145)
- `H_FUNC_CREATEREMOTETHREAD` (line 146)
- `H_FUNC_CREATETOOLHELP32SNAPSHOT` (line 147)
- `H_FUNC_PROCESS32FIRSTW` (line 148)
- `H_FUNC_PROCESS32NEXTW` (line 149)
- `H_FUNC_CREATEPIPE` (line 150)
- `H_FUNC_CREATEPROCESSW` (line 151)
- `H_FUNC_CREATEFILEW` (line 152)
- `H_FUNC_GETFULLPATHNAMEW` (line 153)
- `H_FUNC_GETFILESIZE` (line 154)
- `H_FUNC_GETFILESIZEEX` (line 155)
- `H_FUNC_CREATENAMEDPIPEW` (line 156)
- `H_FUNC_CONVERTFIBERTOTHREAD` (line 157)
- `H_FUNC_CREATEFIBEREX` (line 158)
- `H_FUNC_READFILE` (line 159)
- `H_FUNC_VIRTUALALLOCEX` (line 160)
- `H_FUNC_WAITFORSINGLEOBJECTEX` (line 161)
- `H_FUNC_GETCOMPUTERNAMEEXA` (line 162)
- `H_FUNC_EXITPROCESS` (line 163)
- `H_FUNC_GETEXITCODEPROCESS` (line 164)
- `H_FUNC_GETEXITCODETHREAD` (line 165)
- `H_FUNC_CONVERTTHREADTOFIBEREX` (line 166)
- `H_FUNC_SWITCHTOFIBER` (line 167)
- `H_FUNC_DELETEFIBER` (line 168)
- `H_FUNC_ALLOCCONSOLE` (line 169)
- `H_FUNC_FREECONSOLE` (line 170)
- `H_FUNC_GETCONSOLEWINDOW` (line 171)
- `H_FUNC_GETSTDHANDLE` (line 172)
- `H_FUNC_SETSTDHANDLE` (line 173)
- `H_FUNC_WAITNAMEDPIPEW` (line 174)
- `H_FUNC_PEEKNAMEDPIPE` (line 175)
- `H_FUNC_DISCONNECTNAMEDPIPE` (line 176)
- `H_FUNC_WRITEFILE` (line 177)
- `H_FUNC_CONNECTNAMEDPIPE` (line 178)
- `H_FUNC_FREELIBRARY` (line 179)
- `H_FUNC_GETCURRENTDIRECTORYW` (line 180)
- `H_FUNC_GETFILEATTRIBUTESW` (line 181)
- `H_FUNC_FINDFIRSTFILEW` (line 182)
- `H_FUNC_FINDNEXTFILEW` (line 183)
- `H_FUNC_FINDCLOSE` (line 184)
- `H_FUNC_FILETIMETOSYSTEMTIME` (line 185)
- `H_FUNC_SYSTEMTIMETOTZSPECIFICLOCALTIME` (line 186)
- `H_FUNC_REMOVEDIRECTORYW` (line 187)
- `H_FUNC_DELETEFILEW` (line 188)
- `H_FUNC_CREATEDIRECTORYW` (line 189)
- `H_FUNC_COPYFILEW` (line 190)
- `H_FUNC_MOVEFILEEXW` (line 191)
- `H_FUNC_SETCURRENTDIRECTORYW` (line 192)
- `H_FUNC_WOW64DISABLEWOW64FSREDIRECTION` (line 193)
- `H_FUNC_WOW64REVERTWOW64FSREDIRECTION` (line 194)
- `H_FUNC_GETMODULEHANDLEA` (line 195)
- `H_FUNC_GETSYSTEMTIMEASFILETIME` (line 196)
- `H_FUNC_GETLOCALTIME` (line 197)
- `H_FUNC_DUPLICATEHANDLE` (line 198)
- `H_FUNC_ATTACHCONSOLE` (line 199)
- `H_FUNC_WRITECONSOLEA` (line 200)
- `H_FUNC_TERMINATEPROCESS` (line 201)
- `H_FUNC_VIRTUALPROTECT` (line 202)
- `H_FUNC_GETTOKENINFORMATION` (line 203)
- `H_FUNC_CREATEPROCESSWITHTOKENW` (line 204)
- `H_FUNC_CREATEPROCESSWITHLOGONW` (line 205)
- `H_FUNC_REVERTTOSELF` (line 206)
- `H_FUNC_GETUSERNAMEA` (line 207)
- `H_FUNC_LOGONUSERW` (line 208)
- `H_FUNC_LOOKUPACCOUNTSIDA` (line 209)
- `H_FUNC_LOOKUPACCOUNTSIDW` (line 210)
- `H_FUNC_OPENTHREADTOKEN` (line 211)
- `H_FUNC_OPENPROCESSTOKEN` (line 212)
- `H_FUNC_ADJUSTTOKENPRIVILEGES` (line 213)
- `H_FUNC_LOOKUPPRIVILEGENAMEA` (line 214)
- `H_FUNC_SYSTEMFUNCTION032` (line 215)
- `H_FUNC_FREESID` (line 216)
- `H_FUNC_SETSECURITYDESCRIPTORSACL` (line 217)
- `H_FUNC_SETSECURITYDESCRIPTORDACL` (line 218)
- `H_FUNC_INITIALIZESECURITYDESCRIPTOR` (line 219)
- `H_FUNC_ADDMANDATORYACE` (line 220)
- `H_FUNC_INITIALIZEACL` (line 221)
- `H_FUNC_ALLOCATEANDINITIALIZESID` (line 222)
- `H_FUNC_CHECKTOKENMEMBERSHIP` (line 223)
- `H_FUNC_SETENTRIESINACLW` (line 224)
- `H_FUNC_SETTHREADTOKEN` (line 225)
- `H_FUNC_LSANTSTATUSTOWINERROR` (line 226)
- `H_FUNC_EQUALSID` (line 227)
- `H_FUNC_CONVERTSIDTOSTRINGSIDW` (line 228)
- `H_FUNC_GETSIDSUBAUTHORITYCOUNT` (line 229)
- `H_FUNC_GETSIDSUBAUTHORITY` (line 230)
- `H_FUNC_LOOKUPPRIVILEGEVALUEA` (line 231)
- `H_FUNC_SAFEARRAYACCESSDATA` (line 232)
- `H_FUNC_SAFEARRAYUNACCESSDATA` (line 233)
- `H_FUNC_SAFEARRAYCREATE` (line 234)
- `H_FUNC_SAFEARRAYPUTELEMENT` (line 235)
- `H_FUNC_SAFEARRAYCREATEVECTOR` (line 236)
- `H_FUNC_SAFEARRAYDESTROY` (line 237)
- `H_FUNC_SYSALLOCSTRING` (line 238)
- `H_FUNC_COMMANDLINETOARGVW` (line 239)
- `H_FUNC_SHOWWINDOW` (line 240)
- `H_FUNC_GETSYSTEMMETRICS` (line 241)
- `H_FUNC_GETDC` (line 242)
- `H_FUNC_RELEASEDC` (line 243)
- `H_FUNC_GETCURRENTOBJECT` (line 244)
- `H_FUNC_GETOBJECTW` (line 245)
- `H_FUNC_CREATECOMPATIBLEDC` (line 246)
- `H_FUNC_CREATEDIBSECTION` (line 247)
- `H_FUNC_SELECTOBJECT` (line 248)
- `H_FUNC_BITBLT` (line 249)
- `H_FUNC_DELETEOBJECT` (line 250)
- `H_FUNC_DELETEDC` (line 251)
- `H_FUNC_SETPROCESSVALIDCALLTARGETS` (line 252)
- `H_FUNC_CLRCREATEINSTANCE` (line 253)
- `H_FUNC_GETADAPTERSINFO` (line 254)
- `H_FUNC_NETLOCALGROUPENUM` (line 255)
- `H_FUNC_NETGROUPENUM` (line 256)
- `H_FUNC_NETUSERENUM` (line 257)
- `H_FUNC_NETWKSTAUSERENUM` (line 258)
- `H_FUNC_NETSESSIONENUM` (line 259)
- `H_FUNC_NETSHAREENUM` (line 260)
- `H_FUNC_NETAPIBUFFERFREE` (line 261)
- `H_FUNC_WSASTARTUP` (line 262)
- `H_FUNC_WSACLEANUP` (line 263)
- `H_FUNC_WSASOCKETA` (line 264)
- `H_FUNC_WSAGETLASTERROR` (line 265)
- `H_FUNC_IOCTLSOCKET` (line 266)
- `H_FUNC_BIND` (line 267)
- `H_FUNC_LISTEN` (line 268)
- `H_FUNC_ACCEPT` (line 269)
- `H_FUNC_CLOSESOCKET` (line 270)
- `H_FUNC_RECV` (line 271)
- `H_FUNC_SEND` (line 272)
- `H_FUNC_CONNECT` (line 273)
- `H_FUNC_GETADDRINFO` (line 274)
- `H_FUNC_FREEADDRINFO` (line 275)
- `H_FUNC_LSAREGISTERLOGONPROCESS` (line 276)
- `H_FUNC_LSALOOKUPAUTHENTICATIONPACKAGE` (line 277)
- `H_FUNC_LSADEREGISTERLOGONPROCESS` (line 278)
- `H_FUNC_LSACONNECTUNTRUSTED` (line 279)
- `H_FUNC_LSAFREERETURNBUFFER` (line 280)
- `H_FUNC_LSACALLAUTHENTICATIONPACKAGE` (line 281)
- `H_FUNC_LSAGETLOGONSESSIONDATA` (line 282)
- `H_FUNC_LSAENUMERATELOGONSESSIONS` (line 283)
- `H_FUNC_SLEEP` (line 284)
- `H_FUNC_CREATETHREAD` (line 285)
- `H_FUNC_AMSISCANBUFFER` (line 286)
- `H_FUNC_GLOBALFREE` (line 287)
- `H_FUNC_SWPRINTF_S` (line 288)
- `H_COFFAPI_BEACONDATAPARSER` (line 292)
- `H_COFFAPI_BEACONDATAINT` (line 293)
- `H_COFFAPI_BEACONDATASHORT` (line 294)
- `H_COFFAPI_BEACONDATALENGTH` (line 295)
- `H_COFFAPI_BEACONDATAEXTRACT` (line 296)
- `H_COFFAPI_BEACONFORMATALLOC` (line 297)
- `H_COFFAPI_BEACONFORMATRESET` (line 299)
- `H_COFFAPI_BEACONFORMATFREE` (line 300)
- `H_COFFAPI_BEACONFORMATAPPEND` (line 301)
- `H_COFFAPI_BEACONFORMATPRINTF` (line 302)
- `H_COFFAPI_BEACONFORMATTOSTRING` (line 303)
- `H_COFFAPI_BEACONFORMATINT` (line 304)
- `H_COFFAPI_BEACONPRINTF` (line 305)
- `H_COFFAPI_BEACONOUTPUT` (line 307)
- `H_COFFAPI_BEACONUSETOKEN` (line 308)
- `H_COFFAPI_BEACONREVERTTOKEN` (line 309)
- `H_COFFAPI_BEACONISADMIN` (line 310)
- `H_COFFAPI_BEACONGETSPAWNTO` (line 311)
- `H_COFFAPI_BEACONSPAWNTEMPORARYPROCESS` (line 312)
- `H_COFFAPI_BEACONINJECTPROCESS` (line 313)
- `H_COFFAPI_BEACONINJECTTEMPORARYPROCESS` (line 314)
- `H_COFFAPI_BEACONCLEANUPPROCESS` (line 315)
- `H_COFFAPI_BEACONINFORMATION` (line 316)
- `H_COFFAPI_BEACONADDVALUE` (line 317)
- `H_COFFAPI_BEACONGETVALUE` (line 318)
- `H_COFFAPI_BEACONREMOVEVALUE` (line 319)
- `H_COFFAPI_BEACONDATASTOREGETITEM` (line 320)
- `H_COFFAPI_BEACONDATASTOREPROTECTITEM` (line 321)
- `H_COFFAPI_BEACONDATASTOREUNPROTECTITEM` (line 322)
- `H_COFFAPI_BEACONDATASTOREMAXENTRIES` (line 323)
- `H_COFFAPI_BEACONGETCUSTOMUSERDATA` (line 324)
- `H_COFFAPI_TOWIDECHAR` (line 325)
- `H_COFFAPI_LOADLIBRARYA` (line 327)
- `H_COFFAPI_GETPROCADDRESS` (line 328)
- `H_COFFAPI_GETMODULEHANDLE` (line 329)
- `H_COFFAPI_FREELIBRARY` (line 330)
- `H_COFFAPI_LOCALFREE` (line 331)
- `H_COFFAPI_NTOPENTHREAD` (line 332)
- `H_COFFAPI_NTOPENPROCESS` (line 334)
- `H_COFFAPI_NTTERMINATEPROCESS` (line 335)
- `H_COFFAPI_NTOPENTHREADTOKEN` (line 336)
- `H_COFFAPI_NTOPENPROCESSTOKEN` (line 337)
- `H_COFFAPI_NTDUPLICATETOKEN` (line 338)
- `H_COFFAPI_NTQUEUEAPCTHREAD` (line 339)
- `H_COFFAPI_NTSUSPENDTHREAD` (line 340)
- `H_COFFAPI_NTRESUMETHREAD` (line 341)
- `H_COFFAPI_NTCREATEEVENT` (line 342)
- `H_COFFAPI_NTCREATETHREADEX` (line 343)
- `H_COFFAPI_NTDUPLICATEOBJECT` (line 344)
- `H_COFFAPI_NTGETCONTEXTTHREAD` (line 345)
- `H_COFFAPI_NTSETCONTEXTTHREAD` (line 346)
- `H_COFFAPI_NTQUERYINFORMATIONPROCESS` (line 347)
- `H_COFFAPI_NTQUERYSYSTEMINFORMATION` (line 348)
- `H_COFFAPI_NTWAITFORSINGLEOBJECT` (line 349)
- `H_COFFAPI_NTALLOCATEVIRTUALMEMORY` (line 350)
- `H_COFFAPI_NTWRITEVIRTUALMEMORY` (line 351)
- `H_COFFAPI_NTFREEVIRTUALMEMORY` (line 352)
- `H_COFFAPI_NTUNMAPVIEWOFSECTION` (line 353)
- `H_COFFAPI_NTPROTECTVIRTUALMEMORY` (line 354)
- `H_COFFAPI_NTREADVIRTUALMEMORY` (line 355)
- `H_COFFAPI_NTTERMINATETHREAD` (line 356)
- `H_COFFAPI_NTALERTRESUMETHREAD` (line 357)
- `H_COFFAPI_NTSIGNALANDWAITFORSINGLEOBJECT` (line 358)
- `H_COFFAPI_NTQUERYVIRTUALMEMORY` (line 359)
- `H_COFFAPI_NTQUERYINFORMATIONTOKEN` (line 360)
- `H_COFFAPI_NTQUERYINFORMATIONTHREAD` (line 361)
- `H_COFFAPI_NTQUERYOBJECT` (line 362)
- `H_COFFAPI_NTCLOSE` (line 363)
- `H_COFFAPI_NTSETINFORMATIONTHREAD` (line 364)
- `H_COFFAPI_NTSETINFORMATIONVIRTUALMEMORY` (line 365)
- `H_COFFAPI_NTGETNEXTTHREAD` (line 366)
- `H_MODULE_KERNEL32` (line 367)
- `H_MODULE_NTDLL` (line 369)

#### `Macros.h`
**Path:** `payloads/Demon/include/common/Macros.h`

**Macros:**
- `DEMON_MACROS_H` (line 2)
- `PPEB_PTR` (line 7)
- `PPEB_PTR` (line 9)
- `NT_SUCCESS` (line 11)
- `NtCurrentProcess` (line 13)
- `NtCurrentThread` (line 14)
- `NtGetLastError` (line 15)
- `NtSetLastError` (line 16)
- `NtProcessHeap` (line 19)
- `DLLEXPORT` (line 20)
- `RVA` (line 21)
- `DATA_FREE` (line 23)
- `SEC_DATA` (line 29)
- `U_PTR` (line 31)
- `C_PTR` (line 32)
- `B_PTR` (line 33)
- `DREF_U8` (line 34)
- `DREF_U16` (line 35)
- `HTONS32` (line 36)
- `HTONS16` (line 37)
- `IMAGE_SIZE` (line 38)
- `PRINTF` (line 44)
- `PRINTF_DONT_SEND` (line 45)
- `PRINTF` (line 47)
- `PRINTF_DONT_SEND` (line 48)
- `PRINTF` (line 50)
- `PRINTF_DONT_SEND` (line 51)
- `PRINTF` (line 53)
- `PRINTF_DONT_SEND` (line 54)
- `PRINTF` (line 57)
- `PRINTF_DONT_SEND` (line 58)
- `PUTS` (line 63)
- `PUTS_DONT_SEND` (line 64)
- `PUTS` (line 66)
- `PUTS_DONT_SEND` (line 67)
- `PUTS` (line 69)
- `PUTS_DONT_SEND` (line 70)
- `PUTS` (line 73)
- `PUTS_DONT_SEND` (line 74)
- `PRINT_HEX` (line 78)
- `PRINT_HEX` (line 86)

#### `Native.h`
**Path:** `payloads/Demon/include/common/Native.h`

**Functions:**
- `NtCurrentPeb` (line 7104) `__inline struct _PEB * NtCurrentPeb()` - *17/3/2011 added*
- `GetKUserSharedData` (line 10904) `__inline struct _KUSER_SHARED_DATA * GetKUserSharedData()` - *define SHARED_USER_DATA_VA 0x7FFE0000 define USER_SHARED_DATA ((KUSER_SHARED_DATA * const)SHARED_USER_DATA_VA)*
- `NtGetTickCount` (line 10906) `__forceinline ULONG NtGetTickCount()`

**Macros:**
- `_NTDLL_` (line 21)
- `EXPORT_FN` (line 48)
- `IMPORT_FN` (line 50)
- `PAGE_SIZE` (line 51)
- `EXTERNAL` (line 53)
- `UNREFERENCED_PARAMETER` (line 57)
- `NT_SUCCESS` (line 61)
- `NT_INFORMATION` (line 63)
- `NT_WARNING` (line 64)
- `NT_ERROR` (line 65)
- `ABSOLUTE_TIME` (line 66)
- `RELATIVE_TIME` (line 68)
- `NANOSECONDS` (line 69)
- `MICROSECONDS` (line 71)
- `MILLISECONDS` (line 73)
- `SECONDS` (line 75)
- `ARGUMENT_PRESENT` (line 77)
- `RESTORE_LIST` (line 80)
- `UNLINK` (line 84)
- `ALIGN_TO_POWER2` (line 87)
- `POI` (line 89)
- `IS_PATH_SEPARATOR` (line 91)
- `IS_DOT` (line 93)
- `IS_DOT_DOT` (line 94)
- `IS_PATH_SEPARATOR_U` (line 95)
- `IS_DOT_U` (line 97)
- `IS_DOT_DOT_U` (line 98)
- `jmp_length` (line 99)
- `stc_jc` (line 101)
- `MODIFYBYTE` (line 102)
- `MODIFYWORD` (line 104)
- `MODIFYDWORD` (line 105)
- `MODIFYQWORD` (line 106)
- `PTR_ADD_OFFSET` (line 107)
- `WRITE_JMP` (line 109)
- `GET_JMP` (line 111)
- `ASSERT` (line 112)
- `SHORT_SIZE` (line 120)
- `SHORT_MASK` (line 121)
- `LONG_SIZE` (line 122)
- `LONG_MASK` (line 123)
- `LOWBYTE_MASK` (line 124)
- `FIRSTBYTE` (line 125)
- `SECONDBYTE` (line 127)
- `THIRDBYTE` (line 128)
- `FOURTHBYTE` (line 129)
- `SHORT_LEAST_SIGNIFICANT_BIT` (line 134)
- `SHORT_MOST_SIGNIFICANT_BIT` (line 136)
- `LONG_LEAST_SIGNIFICANT_BIT` (line 137)
- `LONG_3RD_MOST_SIGNIFICANT_BIT` (line 139)
- `LONG_2ND_MOST_SIGNIFICANT_BIT` (line 140)
- `LONG_MOST_SIGNIFICANT_BIT` (line 141)
- `RtlStoreUshort` (line 166)
- `RtlStoreUlong` (line 204)
- `RtlRetrieveUshort` (line 239)
- `RtlRetrieveUlong` (line 276)
- `RtlOffsetToPointer` (line 315)
- `RtlPointerToOffset` (line 346)
- `ANSI_NULL` (line 389)
- `UNICODE_NULL` (line 412)
- `FIELD_OFFSET` (line 448)
- `CONTAINING_RECORD` (line 450)
- `IN_REGION` (line 461)
- `RVATOVA` (line 465)
- `NOP_FUNCTION` (line 469)
- `PAGED_CODE` (line 471)
- `LPC_CLIENT_ID` (line 474)
- `LPC_SIZE_T` (line 475)
- `LPC_PVOID` (line 476)
- `LPC_HANDLE` (line 477)
- `LPC_CLIENT_ID` (line 479)
- `LPC_SIZE_T` (line 480)
- `LPC_PVOID` (line 481)
- `LPC_HANDLE` (line 482)
- `OBJ_INHERIT` (line 484)
- `OBJ_HANDLE_TAGBITS` (line 486)
- `OBJ_PERMANENT` (line 487)
- `OBJ_EXCLUSIVE` (line 488)
- `OBJ_CASE_INSENSITIVE` (line 489)
- `OBJ_OPENIF` (line 490)
- `OBJ_OPENLINK` (line 491)
- `OBJ_KERNEL_HANDLE` (line 492)
- `OBJ_FORCE_ACCESS_CHECK` (line 493)
- `OBJ_VALID_ATTRIBUTES` (line 494)
- `RTL_QUERY_PROCESS_MODULES` (line 495)
- `RTL_QUERY_PROCESS_BACKTRACES` (line 497)
- `RTL_QUERY_PROCESS_HEAP_SUMMARY` (line 498)
- `RTL_QUERY_PROCESS_HEAP_TAGS` (line 499)
- `RTL_QUERY_PROCESS_HEAP_ENTRIES` (line 500)
- `RTL_QUERY_PROCESS_LOCKS` (line 501)
- `RTL_QUERY_PROCESS_MODULES32` (line 502)
- `RTL_QUERY_PROCESS_NONINVASIVE` (line 503)
- `InitializeObjectAttributes` (line 516)
- `___PROCESSOR_NUMBER_DEFINED` (line 533)
- `ANSI_NULL` (line 542)
- `UNICODE_NULL` (line 544)
- `UNICODE_STRING_MAX_BYTES` (line 547)
- `UNICODE_STRING_MAX_CHARS` (line 549)
- `DECLARE_CONST_UNICODE_STRING` (line 551)
- `IsListEmpty` (line 557)
- `InitializeListHead` (line 560)
- `IsListEmpty` (line 563)
- `RemoveHeadList` (line 566)
- `RemoveTailList` (line 570)
- `RemoveEntryList` (line 579)
- `InsertTailList` (line 594)
- `InsertHeadList` (line 610)
- `COUNT_IS_ALIGNED` (line 627)
- `POINTER_IS_ALIGNED` (line 636)
- `ROUND_DOWN_COUNT` (line 638)
- `ROUND_DOWN_POINTER` (line 642)
- `ROUND_UP_COUNT` (line 655)
- `ROUND_UP_POINTER` (line 665)
- `ALIGN_BYTE` (line 667)
- `ALIGN_CHAR` (line 669)
- `ALIGN_DESC_CHAR` (line 670)
- `ALIGN_DWORD` (line 671)
- `ALIGN_LONG` (line 672)
- `ALIGN_LPBYTE` (line 673)
- `ALIGN_LPDWORD` (line 674)
- `ALIGN_LPSTR` (line 675)
- `ALIGN_LPTSTR` (line 676)
- `ALIGN_LPVOID` (line 677)
- `ALIGN_LPWORD` (line 678)
- `ALIGN_TCHAR` (line 679)
- `ALIGN_WCHAR` (line 680)
- `ALIGN_WORD` (line 681)
- `ALIGN_QUAD` (line 682)
- `ALIGN_WORST` (line 683)
- `QUAD_ALIGN` (line 687)
- `EXPORT_VA` (line 693)
- `IMPORT_VA` (line 694)
- `RELOC_VA` (line 695)
- `RESOURCE_VA` (line 696)
- `EXPORT_SIZE` (line 697)
- `IMPORT_SIZE` (line 699)
- `RELOC_SIZE` (line 700)
- `RESOURCE_SIZE` (line 701)
- `DEBUGDIR_VA` (line 702)
- `DEBUGDIR_SIZE` (line 703)
- `IS_VALID_HANDLE` (line 705)
- `SIZEOF_ARRAY` (line 707)
- `_FILESYSTEMFSCTL_` (line 712)
- `FSCTL_REQUEST_OPLOCK_LEVEL_1` (line 713)
- `FSCTL_REQUEST_OPLOCK_LEVEL_2` (line 715)
- `FSCTL_REQUEST_BATCH_OPLOCK` (line 716)
- `FSCTL_OPLOCK_BREAK_ACKNOWLEDGE` (line 717)
- `FSCTL_OPBATCH_ACK_CLOSE_PENDING` (line 718)
- `FSCTL_OPLOCK_BREAK_NOTIFY` (line 719)
- `FSCTL_LOCK_VOLUME` (line 720)
- `FSCTL_UNLOCK_VOLUME` (line 721)
- `FSCTL_DISMOUNT_VOLUME` (line 722)
- `FSCTL_IS_VOLUME_MOUNTED` (line 724)
- `FSCTL_IS_PATHNAME_VALID` (line 725)
- `FSCTL_MARK_VOLUME_DIRTY` (line 726)
- `FSCTL_QUERY_RETRIEVAL_POINTERS` (line 728)
- `FSCTL_GET_COMPRESSION` (line 729)
- `FSCTL_SET_COMPRESSION` (line 730)
- `FSCTL_SET_BOOTLOADER_ACCESSED` (line 733)
- `FSCTL_OPLOCK_BREAK_ACK_NO_2` (line 734)
- `FSCTL_INVALIDATE_VOLUMES` (line 735)
- `FSCTL_QUERY_FAT_BPB` (line 736)
- `FSCTL_REQUEST_FILTER_OPLOCK` (line 737)
- `FSCTL_FILESYSTEM_GET_STATISTICS` (line 738)
- `FSCTL_GET_NTFS_VOLUME_DATA` (line 741)
- `FSCTL_GET_NTFS_FILE_RECORD` (line 742)
- `FSCTL_GET_VOLUME_BITMAP` (line 743)
- `FSCTL_GET_RETRIEVAL_POINTERS` (line 744)
- `FSCTL_MOVE_FILE` (line 745)
- `FSCTL_IS_VOLUME_DIRTY` (line 746)
- `FSCTL_ALLOW_EXTENDED_DASD_IO` (line 748)
- `FSCTL_FIND_FILES_BY_SID` (line 754)
- `FSCTL_SET_OBJECT_ID` (line 757)
- `FSCTL_GET_OBJECT_ID` (line 758)
- `FSCTL_DELETE_OBJECT_ID` (line 759)
- `FSCTL_SET_REPARSE_POINT` (line 760)
- `FSCTL_GET_REPARSE_POINT` (line 761)
- `FSCTL_DELETE_REPARSE_POINT` (line 762)
- `FSCTL_ENUM_USN_DATA` (line 763)
- `FSCTL_SECURITY_ID_CHECK` (line 764)
- `FSCTL_READ_USN_JOURNAL` (line 765)
- `FSCTL_SET_OBJECT_ID_EXTENDED` (line 766)
- `FSCTL_CREATE_OR_GET_OBJECT_ID` (line 767)
- `FSCTL_SET_SPARSE` (line 768)
- `FSCTL_SET_ZERO_DATA` (line 769)
- `FSCTL_QUERY_ALLOCATED_RANGES` (line 770)
- `FSCTL_ENABLE_UPGRADE` (line 771)
- `FSCTL_SET_ENCRYPTION` (line 773)
- `FSCTL_ENCRYPTION_FSCTL_IO` (line 774)
- `FSCTL_WRITE_RAW_ENCRYPTED` (line 775)
- `FSCTL_READ_RAW_ENCRYPTED` (line 776)
- `FSCTL_CREATE_USN_JOURNAL` (line 777)
- `FSCTL_READ_FILE_USN_DATA` (line 778)
- `FSCTL_WRITE_USN_CLOSE_RECORD` (line 779)
- `FSCTL_EXTEND_VOLUME` (line 780)
- `FSCTL_QUERY_USN_JOURNAL` (line 781)
- `FSCTL_DELETE_USN_JOURNAL` (line 782)
- `FSCTL_MARK_HANDLE` (line 783)
- `FSCTL_SIS_COPYFILE` (line 784)
- `FSCTL_SIS_LINK_FILES` (line 785)
- `FSCTL_RECALL_FILE` (line 789)
- `FSCTL_READ_FROM_PLEX` (line 791)
- `FSCTL_FILE_PREFETCH` (line 792)
- `FSCTL_MAKE_MEDIA_COMPATIBLE` (line 796)
- `FSCTL_SET_DEFECT_MANAGEMENT` (line 797)
- `FSCTL_QUERY_SPARING_INFO` (line 798)
- `FSCTL_QUERY_ON_DISK_VOLUME_INFO` (line 799)
- `FSCTL_SET_VOLUME_COMPRESSION_STATE` (line 800)
- `FSCTL_TXFS_MODIFY_RM` (line 802)
- `FSCTL_TXFS_QUERY_RM_INFORMATION` (line 803)
- `FSCTL_TXFS_ROLLFORWARD_REDO` (line 805)
- `FSCTL_TXFS_ROLLFORWARD_UNDO` (line 806)
- `FSCTL_TXFS_START_RM` (line 807)
- `FSCTL_TXFS_SHUTDOWN_RM` (line 808)
- `FSCTL_TXFS_READ_BACKUP_INFORMATION` (line 809)
- `FSCTL_TXFS_WRITE_BACKUP_INFORMATION` (line 810)
- `FSCTL_TXFS_CREATE_SECONDARY_RM` (line 811)
- `FSCTL_TXFS_GET_METADATA_INFO` (line 812)
- `FSCTL_TXFS_GET_TRANSACTED_VERSION` (line 813)
- `FSCTL_TXFS_SAVEPOINT_INFORMATION` (line 815)
- `FSCTL_TXFS_CREATE_MINIVERSION` (line 816)
- `FSCTL_TXFS_TRANSACTION_ACTIVE` (line 820)
- `FSCTL_SET_ZERO_ON_DEALLOCATION` (line 821)
- `FSCTL_SET_REPAIR` (line 822)
- `FSCTL_GET_REPAIR` (line 823)
- `FSCTL_WAIT_FOR_REPAIR` (line 824)
- `FSCTL_INITIATE_REPAIR` (line 826)
- `FSCTL_CSC_INTERNAL` (line 827)
- `FSCTL_SHRINK_VOLUME` (line 828)
- `FSCTL_SET_SHORT_NAME_BEHAVIOR` (line 829)
- `FSCTL_DFSR_SET_GHOST_HANDLE_STATE` (line 830)
- `FSCTL_TXFS_LIST_TRANSACTION_LOCKED_FILES` (line 835)
- `FSCTL_TXFS_LIST_TRANSACTIONS` (line 838)
- `FSCTL_QUERY_PAGEFILE_ENCRYPTION` (line 839)
- `FSCTL_RESET_VOLUME_ALLOCATION_HINTS` (line 843)
- `FSCTL_QUERY_DEPENDENT_VOLUME` (line 847)
- `FSCTL_SD_GLOBAL_CHANGE` (line 848)
- `FSCTL_TXFS_READ_BACKUP_INFORMATION2` (line 852)
- `FSCTL_LOOKUP_STREAM_FROM_CLUSTER` (line 856)
- `FSCTL_TXFS_WRITE_BACKUP_INFORMATION2` (line 857)
- `FSCTL_FILE_TYPE_NOTIFICATION` (line 858)
- `FSCTL_GET_BOOT_AREA_INFO` (line 865)
- `FSCTL_GET_RETRIEVAL_POINTER_BASE` (line 866)
- `FSCTL_SET_PERSISTENT_VOLUME_STATE` (line 867)
- `FSCTL_QUERY_PERSISTENT_VOLUME_STATE` (line 868)
- `FSCTL_REQUEST_OPLOCK` (line 869)
- `FSCTL_CSV_TUNNEL_REQUEST` (line 871)
- `FSCTL_IS_CSV_FILE` (line 873)
- `FSCTL_QUERY_FILE_SYSTEM_RECOGNITION` (line 874)
- `FSCTL_CSV_GET_VOLUME_PATH_NAME` (line 876)
- `FSCTL_CSV_GET_VOLUME_NAME_FOR_VOLUME_MOUNT_POINT` (line 877)
- `FSCTL_CSV_GET_VOLUME_PATH_NAMES_FOR_VOLUME_NAME` (line 878)
- `FSCTL_IS_FILE_ON_CSV_VOLUME` (line 879)
- `FSCTL_MARK_AS_SYSTEM_HIVE` (line 882)
- `CSV_NAMESPACE_INFO_V1` (line 896)
- `CSV_INVALID_DEVICE_NUMBER` (line 898)
- `USN_PAGE_SIZE` (line 1095)
- `USN_REASON_DATA_OVERWRITE` (line 1097)
- `USN_REASON_DATA_EXTEND` (line 1099)
- `USN_REASON_DATA_TRUNCATION` (line 1100)
- `USN_REASON_NAMED_DATA_OVERWRITE` (line 1101)
- `USN_REASON_NAMED_DATA_EXTEND` (line 1102)
- `USN_REASON_NAMED_DATA_TRUNCATION` (line 1103)
- `USN_REASON_FILE_CREATE` (line 1104)
- `USN_REASON_FILE_DELETE` (line 1105)
- `USN_REASON_EA_CHANGE` (line 1106)
- `USN_REASON_SECURITY_CHANGE` (line 1107)
- `USN_REASON_RENAME_OLD_NAME` (line 1108)
- `USN_REASON_RENAME_NEW_NAME` (line 1109)
- `USN_REASON_INDEXABLE_CHANGE` (line 1110)
- `USN_REASON_BASIC_INFO_CHANGE` (line 1111)
- `USN_REASON_HARD_LINK_CHANGE` (line 1112)
- `USN_REASON_COMPRESSION_CHANGE` (line 1113)
- `USN_REASON_ENCRYPTION_CHANGE` (line 1114)
- `USN_REASON_OBJECT_ID_CHANGE` (line 1115)
- `USN_REASON_REPARSE_POINT_CHANGE` (line 1116)
- `USN_REASON_STREAM_CHANGE` (line 1117)
- `USN_REASON_TRANSACTED_CHANGE` (line 1118)
- `USN_REASON_CLOSE` (line 1119)
- `USN_DELETE_FLAG_DELETE` (line 1139)
- `USN_DELETE_FLAG_NOTIFY` (line 1141)
- `USN_DELETE_VALID_FLAGS` (line 1142)
- `USN_SOURCE_DATA_MANAGEMENT` (line 1163)
- `USN_SOURCE_AUXILIARY_DATA` (line 1165)
- `USN_SOURCE_REPLICATION_MANAGEMENT` (line 1166)
- `MARK_HANDLE_PROTECT_CLUSTERS` (line 1167)
- `MARK_HANDLE_TXF_SYSTEM_LOG` (line 1169)
- `MARK_HANDLE_NOT_TXF_SYSTEM_LOG` (line 1170)
- `MARK_HANDLE_REALTIME` (line 1175)
- `MARK_HANDLE_NOT_REALTIME` (line 1177)
- `NO_8DOT3_NAME_PRESENT` (line 1178)
- `REMOVED_8DOT3_NAME` (line 1180)
- `PERSISTENT_VOLUME_STATE_SHORT_NAME_CREATION_DISABLED` (line 1181)
- `VOLUME_IS_DIRTY` (line 1197)
- `VOLUME_UPGRADE_SCHEDULED` (line 1199)
- `VOLUME_SESSION_OPEN` (line 1200)
- `FILE_PREFETCH_TYPE_FOR_CREATE` (line 1217)
- `FILE_PREFETCH_TYPE_FOR_DIRENUM` (line 1219)
- `FILE_PREFETCH_TYPE_FOR_CREATE_EX` (line 1220)
- `FILE_PREFETCH_TYPE_FOR_DIRENUM_EX` (line 1221)
- `FILE_PREFETCH_TYPE_MAX` (line 1222)
- `FILESYSTEM_STATISTICS_TYPE_NTFS` (line 1250)
- `FILESYSTEM_STATISTICS_TYPE_FAT` (line 1252)
- `FILESYSTEM_STATISTICS_TYPE_EXFAT` (line 1253)
- `FILE_SET_ENCRYPTION` (line 1448)
- `FILE_CLEAR_ENCRYPTION` (line 1450)
- `STREAM_SET_ENCRYPTION` (line 1451)
- `STREAM_CLEAR_ENCRYPTION` (line 1452)
- `MAXIMUM_ENCRYPTION_VALUE` (line 1453)
- `ENCRYPTION_FORMAT_DEFAULT` (line 1461)
- `COMPRESSION_FORMAT_SPARSE` (line 1463)
- `COPYFILE_SIS_LINK` (line 1519)
- `COPYFILE_SIS_REPLACE` (line 1521)
- `COPYFILE_SIS_FLAGS` (line 1522)
- `SET_REPAIR_ENABLED` (line 1558)
- `SET_REPAIR_VOLUME_BITMAP_SCAN` (line 1561)
- `SET_REPAIR_DELETE_CROSSLINK` (line 1562)
- `SET_REPAIR_WARN_ABOUT_DATA_LOSS` (line 1563)
- `SET_REPAIR_DISABLED_AND_BUGCHECK_ON_CORRUPT` (line 1564)
- `SET_REPAIR_VALID_MASK` (line 1565)
- `TXFS_RM_FLAG_LOGGING_MODE` (line 1582)
- `TXFS_RM_FLAG_RENAME_RM` (line 1584)
- `TXFS_RM_FLAG_LOG_CONTAINER_COUNT_MAX` (line 1585)
- `TXFS_RM_FLAG_LOG_CONTAINER_COUNT_MIN` (line 1586)
- `TXFS_RM_FLAG_LOG_GROWTH_INCREMENT_NUM_CONTAINERS` (line 1587)
- `TXFS_RM_FLAG_LOG_GROWTH_INCREMENT_PERCENT` (line 1588)
- `TXFS_RM_FLAG_LOG_AUTO_SHRINK_PERCENTAGE` (line 1589)
- `TXFS_RM_FLAG_LOG_NO_CONTAINER_COUNT_MAX` (line 1590)
- `TXFS_RM_FLAG_LOG_NO_CONTAINER_COUNT_MIN` (line 1591)
- `TXFS_RM_FLAG_GROW_LOG` (line 1592)
- `TXFS_RM_FLAG_SHRINK_LOG` (line 1593)
- `TXFS_RM_FLAG_ENFORCE_MINIMUM_SIZE` (line 1594)
- `TXFS_RM_FLAG_PRESERVE_CHANGES` (line 1595)
- `TXFS_RM_FLAG_RESET_RM_AT_NEXT_START` (line 1596)
- `TXFS_RM_FLAG_DO_NOT_RESET_RM_AT_NEXT_START` (line 1597)
- `TXFS_RM_FLAG_PREFER_CONSISTENCY` (line 1598)
- `TXFS_RM_FLAG_PREFER_AVAILABILITY` (line 1599)
- `TXFS_LOGGING_MODE_SIMPLE` (line 1600)
- `TXFS_LOGGING_MODE_FULL` (line 1602)
- `TXFS_TRANSACTION_STATE_NONE` (line 1603)
- `TXFS_TRANSACTION_STATE_ACTIVE` (line 1605)
- `TXFS_TRANSACTION_STATE_PREPARED` (line 1606)
- `TXFS_TRANSACTION_STATE_NOTACTIVE` (line 1607)
- `TXFS_MODIFY_RM_VALID_FLAGS` (line 1608)
- `TXFS_RM_STATE_NOT_STARTED` (line 1684)
- `TXFS_RM_STATE_STARTING` (line 1686)
- `TXFS_RM_STATE_ACTIVE` (line 1687)
- `TXFS_RM_STATE_SHUTTING_DOWN` (line 1688)
- `TXFS_QUERY_RM_INFORMATION_VALID_FLAGS` (line 1689)
- `TXFS_ROLLFORWARD_REDO_FLAG_USE_LAST_REDO_LSN` (line 1794)
- `TXFS_ROLLFORWARD_REDO_FLAG_USE_LAST_VIRTUAL_CLOCK` (line 1796)
- `TXFS_ROLLFORWARD_REDO_VALID_FLAGS` (line 1797)
- `TXFS_START_RM_FLAG_LOG_CONTAINER_COUNT_MAX` (line 1809)
- `TXFS_START_RM_FLAG_LOG_CONTAINER_COUNT_MIN` (line 1811)
- `TXFS_START_RM_FLAG_LOG_CONTAINER_SIZE` (line 1812)
- `TXFS_START_RM_FLAG_LOG_GROWTH_INCREMENT_NUM_CONTAINERS` (line 1813)
- `TXFS_START_RM_FLAG_LOG_GROWTH_INCREMENT_PERCENT` (line 1814)
- `TXFS_START_RM_FLAG_LOG_AUTO_SHRINK_PERCENTAGE` (line 1815)
- `TXFS_START_RM_FLAG_LOG_NO_CONTAINER_COUNT_MAX` (line 1816)
- `TXFS_START_RM_FLAG_LOG_NO_CONTAINER_COUNT_MIN` (line 1817)
- `TXFS_START_RM_FLAG_RECOVER_BEST_EFFORT` (line 1818)
- `TXFS_START_RM_FLAG_LOGGING_MODE` (line 1820)
- `TXFS_START_RM_FLAG_PRESERVE_CHANGES` (line 1821)
- `TXFS_START_RM_FLAG_PREFER_CONSISTENCY` (line 1822)
- `TXFS_START_RM_FLAG_PREFER_AVAILABILITY` (line 1824)
- `TXFS_START_RM_VALID_FLAGS` (line 1825)
- `TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY_FLAG_CREATED` (line 1960)
- `TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY_FLAG_DELETED` (line 1962)
- `TXFS_TRANSACTED_VERSION_NONTRANSACTED` (line 2107)
- `TXFS_TRANSACTED_VERSION_UNCOMMITTED` (line 2109)
- `TXFS_SAVEPOINT_SET` (line 2149)
- `TXFS_SAVEPOINT_ROLLBACK` (line 2156)
- `TXFS_SAVEPOINT_CLEAR` (line 2163)
- `TXFS_SAVEPOINT_CLEAR_ALL` (line 2169)
- `OPLOCK_LEVEL_CACHE_READ` (line 2225)
- `OPLOCK_LEVEL_CACHE_HANDLE` (line 2227)
- `OPLOCK_LEVEL_CACHE_WRITE` (line 2228)
- `REQUEST_OPLOCK_INPUT_FLAG_REQUEST` (line 2229)
- `REQUEST_OPLOCK_INPUT_FLAG_ACK` (line 2231)
- `REQUEST_OPLOCK_INPUT_FLAG_COMPLETE_ACK_ON_CLOSE` (line 2232)
- `REQUEST_OPLOCK_CURRENT_VERSION` (line 2233)
- `REQUEST_OPLOCK_OUTPUT_FLAG_ACK_REQUIRED` (line 2259)
- `REQUEST_OPLOCK_OUTPUT_FLAG_MODES_PROVIDED` (line 2261)
- `SD_GLOBAL_CHANGE_TYPE_MACHINE_SID` (line 2280)
- `ENCRYPTED_DATA_INFO_SPARSE_FILE` (line 2402)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_PAGE_FILE` (line 2426)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_DENY_DEFRAG_SET` (line 2428)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_FS_SYSTEM_FILE` (line 2429)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_TXF_SYSTEM_FILE` (line 2430)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_MASK` (line 2431)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_DATA` (line 2433)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_INDEX` (line 2434)
- `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_SYSTEM` (line 2435)
- `FILE_TYPE_NOTIFICATION_FLAG_USAGE_BEGIN` (line 2452)
- `FILE_TYPE_NOTIFICATION_FLAG_USAGE_END` (line 2454)
- `LOCK_QUEUE_WAIT` (line 2713)
- `LOCK_QUEUE_WAIT_BIT` (line 2715)
- `LOCK_QUEUE_OWNER` (line 2716)
- `LOCK_QUEUE_OWNER_BIT` (line 2718)
- `LOCK_QUEUE_TIMER_LOCK_SHIFT` (line 2719)
- `LOCK_QUEUE_TIMER_TABLE_LOCKS` (line 2721)
- `PROCESS_TERMINATE` (line 2874)
- `PROCESS_CREATE_THREAD` (line 2877)
- `PROCESS_SET_SESSIONID` (line 2878)
- `PROCESS_VM_OPERATION` (line 2879)
- `PROCESS_VM_READ` (line 2880)
- `PROCESS_VM_WRITE` (line 2881)
- `PROCESS_DUP_HANDLE` (line 2882)
- `PROCESS_CREATE_PROCESS` (line 2883)
- `PROCESS_SET_QUOTA` (line 2884)
- `PROCESS_SET_INFORMATION` (line 2885)
- `PROCESS_QUERY_INFORMATION` (line 2886)
- `PROCESS_SET_PORT` (line 2887)
- `PROCESS_SUSPEND_RESUME` (line 2888)
- `NtCurrentThread` (line 2889)
- `NtCurrentProcess` (line 2891)
- `ZwCurrentProcess` (line 2892)
- `ZwCurrentThread` (line 2893)
- `NtLastError` (line 2896)
- `NtLastStatus` (line 2897)
- `NtCurrentPID` (line 2900)
- `NtCurrentPID` (line 2902)
- `THREAD_TERMINATE` (line 2904)
- `THREAD_SUSPEND_RESUME` (line 2906)
- `THREAD_ALERT` (line 2907)
- `THREAD_GET_CONTEXT` (line 2908)
- `THREAD_SET_CONTEXT` (line 2909)
- `THREAD_SET_INFORMATION` (line 2910)
- `THREAD_QUERY_INFORMATION` (line 2911)
- `THREAD_SET_THREAD_TOKEN` (line 2912)
- `THREAD_IMPERSONATE` (line 2913)
- `THREAD_DIRECT_IMPERSONATION` (line 2914)
- `JOB_OBJECT_ASSIGN_PROCESS` (line 2915)
- `JOB_OBJECT_SET_ATTRIBUTES` (line 2917)
- `JOB_OBJECT_QUERY` (line 2918)
- `JOB_OBJECT_TERMINATE` (line 2919)
- `JOB_OBJECT_SET_SECURITY_ATTRIBUTES` (line 2920)
- `JOB_OBJECT_ALL_ACCESS` (line 2922)
- `PEB_STDIO_HANDLE_NATIVE` (line 2924)
- `PEB_STDIO_HANDLE_SUBSYS` (line 2926)
- `PEB_STDIO_HANDLE_PM` (line 2927)
- `PEB_STDIO_HANDLE_RESERVED` (line 2928)
- `GDI_HANDLE_BUFFER_SIZE32` (line 2929)
- `GDI_HANDLE_BUFFER_SIZE64` (line 2931)
- `GDI_HANDLE_BUFFER_SIZE` (line 2934)
- `GDI_HANDLE_BUFFER_SIZE` (line 2936)
- `FOREGROUND_BASE_PRIORITY` (line 2942)
- `NORMAL_BASE_PRIORITY` (line 2944)
- `FILE_READ_ACCESS` (line 2947)
- `FILE_SUPERSEDE` (line 3232)
- `FILE_OPEN` (line 3234)
- `FILE_CREATE` (line 3235)
- `FILE_OPEN_IF` (line 3236)
- `FILE_OVERWRITE` (line 3237)
- `FILE_OVERWRITE_IF` (line 3238)
- `FILE_MAXIMUM_DISPOSITION` (line 3239)
- `FILE_DIRECTORY_FILE` (line 3240)
- `FILE_WRITE_THROUGH` (line 3242)
- `FILE_SEQUENTIAL_ONLY` (line 3243)
- `FILE_NO_INTERMEDIATE_BUFFERING` (line 3244)
- `FILE_SYNCHRONOUS_IO_ALERT` (line 3245)
- `FILE_SYNCHRONOUS_IO_NONALERT` (line 3247)
- `FILE_NON_DIRECTORY_FILE` (line 3248)
- `FILE_CREATE_TREE_CONNECTION` (line 3249)
- `FILE_COMPLETE_IF_OPLOCKED` (line 3250)
- `FILE_NO_EA_KNOWLEDGE` (line 3252)
- `FILE_OPEN_FOR_RECOVERY` (line 3253)
- `FILE_RANDOM_ACCESS` (line 3254)
- `FILE_DELETE_ON_CLOSE` (line 3255)
- `FILE_OPEN_BY_FILE_ID` (line 3257)
- `FILE_OPEN_FOR_BACKUP_INTENT` (line 3258)
- `FILE_NO_COMPRESSION` (line 3259)
- `FILE_RESERVE_OPFILTER` (line 3260)
- `FILE_OPEN_REPARSE_POINT` (line 3262)
- `FILE_OPEN_NO_RECALL` (line 3263)
- `FILE_OPEN_FOR_FREE_SPACE_QUERY` (line 3264)
- `FILE_COPY_STRUCTURED_STORAGE` (line 3265)
- `FILE_STRUCTURED_STORAGE` (line 3268)
- `FILE_VALID_OPTION_FLAGS` (line 3269)
- `FILE_VALID_PIPE_OPTION_FLAGS` (line 3271)
- `FILE_VALID_MAILSLOT_OPTION_FLAGS` (line 3272)
- `FILE_VALID_SET_FLAGS` (line 3273)
- `WIN32_CLIENT_INFO_LENGTH` (line 3274)
- `PIO_APC_ROUTINE_DEFINED` (line 3276)
- `IO_COMPLETION_QUERY_STATE` (line 3293)
- `IO_COMPLETION_MODIFY_STATE` (line 3295)
- `IO_COMPLETION_ALL_ACCESS` (line 3296)
- `SEMAPHORE_QUERY_STATE` (line 3399)
- `SEMAPHORE_MODIFY_STATE` (line 3401)
- `SEMAPHORE_ALL_ACCESS` (line 3402)
- `MUTANT_QUERY_STATE` (line 3413)
- `MUTANT_ALL_ACCESS` (line 3415)
- `TIMER_QUERY_STATE` (line 3428)
- `TIMER_MODIFY_STATE` (line 3430)
- `TIMER_ALL_ACCESS` (line 3431)
- `OBJ_NAME_PATH_SEPARATOR` (line 3448)
- `OBJ_MAX_REPARSE_ATTEMPTS` (line 3450)
- `OBJECT_TYPE_CREATE` (line 3451)
- `OBJECT_TYPE_ALL_ACCESS` (line 3452)
- `DIRECTORY_QUERY` (line 3453)
- `DIRECTORY_TRAVERSE` (line 3455)
- `DIRECTORY_CREATE_OBJECT` (line 3456)
- `DIRECTORY_CREATE_SUBDIRECTORY` (line 3457)
- `DIRECTORY_ALL_ACCESS` (line 3458)
- `SYMBOLIC_LINK_QUERY` (line 3460)
- `SYMBOLIC_LINK_ALL_ACCESS` (line 3461)
- `MDL_HASH_TABLE_SIZE` (line 3616)
- `MDL_HASH_MASK` (line 3618)
- `MDL_HASH_INDEX` (line 3619)
- `HEAP_MAKE_TAG_FLAGS` (line 3622)
- `RTL_HEAP_MAKE_TAG` (line 3624)
- `MAXIMUM_LEADBYTES` (line 3685)
- `RTL_RANGE_LIST_SHARED_OK` (line 3709)
- `RTL_RANGE_LIST_NULL_CONFLICT_OK` (line 3711)
- `SE_CREATE_TOKEN_NAME` (line 3845)
- `SE_ASSIGNPRIMARYTOKEN_NAME` (line 3847)
- `SE_LOCK_MEMORY_NAME` (line 3848)
- `SE_INCREASE_QUOTA_NAME` (line 3849)
- `SE_UNSOLICITED_INPUT_NAME` (line 3850)
- `SE_MACHINE_ACCOUNT_NAME` (line 3851)
- `SE_TCB_NAME` (line 3852)
- `SE_SECURITY_NAME` (line 3853)
- `SE_TAKE_OWNERSHIP_NAME` (line 3854)
- `SE_LOAD_DRIVER_NAME` (line 3855)
- `SE_SYSTEM_PROFILE_NAME` (line 3856)
- `SE_SYSTEMTIME_NAME` (line 3857)
- `SE_PROF_SINGLE_PROCESS_NAME` (line 3858)
- `SE_INC_BASE_PRIORITY_NAME` (line 3859)
- `SE_CREATE_PAGEFILE_NAME` (line 3860)
- `SE_CREATE_PERMANENT_NAME` (line 3861)
- `SE_BACKUP_NAME` (line 3862)
- `SE_RESTORE_NAME` (line 3863)
- `SE_SHUTDOWN_NAME` (line 3864)
- `SE_DEBUG_NAME` (line 3865)
- `SE_AUDIT_NAME` (line 3866)
- `SE_SYSTEM_ENVIRONMENT_NAME` (line 3867)
- `SE_CHANGE_NOTIFY_NAME` (line 3868)
- `SE_REMOTE_SHUTDOWN_NAME` (line 3869)
- `SE_UNDOCK_NAME` (line 3870)
- `SE_SYNC_AGENT_NAME` (line 3871)
- `SE_ENABLE_DELEGATION_NAME` (line 3872)
- `SE_MANAGE_VOLUME_NAME` (line 3873)
- `SE_IMPERSONATE_NAME` (line 3874)
- `SE_CREATE_GLOBAL_NAME` (line 3878)
- `SE_MIN_WELL_KNOWN_PRIVILEGE` (line 3881)
- `SE_CREATE_TOKEN_PRIVILEGE` (line 3883)
- `SE_ASSIGNPRIMARYTOKEN_PRIVILEGE` (line 3884)
- `SE_LOCK_MEMORY_PRIVILEGE` (line 3885)
- `SE_INCREASE_QUOTA_PRIVILEGE` (line 3886)
- `SE_MACHINE_ACCOUNT_PRIVILEGE` (line 3887)
- `SE_TCB_PRIVILEGE` (line 3889)
- `SE_SECURITY_PRIVILEGE` (line 3890)
- `SE_TAKE_OWNERSHIP_PRIVILEGE` (line 3891)
- `SE_LOAD_DRIVER_PRIVILEGE` (line 3892)
- `SE_SYSTEM_PROFILE_PRIVILEGE` (line 3893)
- `SE_SYSTEMTIME_PRIVILEGE` (line 3894)
- `SE_PROF_SINGLE_PROCESS_PRIVILEGE` (line 3895)
- `SE_INC_BASE_PRIORITY_PRIVILEGE` (line 3896)
- `SE_CREATE_PAGEFILE_PRIVILEGE` (line 3897)
- `SE_CREATE_PERMANENT_PRIVILEGE` (line 3898)
- `SE_BACKUP_PRIVILEGE` (line 3899)
- `SE_RESTORE_PRIVILEGE` (line 3900)
- `SE_SHUTDOWN_PRIVILEGE` (line 3901)
- `SE_DEBUG_PRIVILEGE` (line 3902)
- `SE_AUDIT_PRIVILEGE` (line 3903)
- `SE_SYSTEM_ENVIRONMENT_PRIVILEGE` (line 3904)
- `SE_CHANGE_NOTIFY_PRIVILEGE` (line 3905)
- `SE_REMOTE_SHUTDOWN_PRIVILEGE` (line 3906)
- `SE_UNDOCK_PRIVILEGE` (line 3907)
- `SE_SYNC_AGENT_PRIVILEGE` (line 3908)
- `SE_ENABLE_DELEGATION_PRIVILEGE` (line 3909)
- `SE_MANAGE_VOLUME_PRIVILEGE` (line 3910)
- `SE_IMPERSONATE_PRIVILEGE` (line 3911)
- `SE_CREATE_GLOBAL_PRIVILEGE` (line 3912)
- `SE_TRUSTED_CREDMAN_ACCESS_PRIVILEGE` (line 3913)
- `SE_RELABEL_PRIVILEGE` (line 3914)
- `SE_INC_WORKING_SET_PRIVILEGE` (line 3915)
- `SE_TIME_ZONE_PRIVILEGE` (line 3916)
- `SE_CREATE_SYMBOLIC_LINK_PRIVILEGE` (line 3917)
- `SE_MAX_WELL_KNOWN_PRIVILEGE` (line 3918)
- `CACHE_FULLY_ASSOCIATIVE` (line 4713)
- `PROCESSOR_INTEL_386` (line 4739)
- `PROCESSOR_INTEL_486` (line 4741)
- `PROCESSOR_INTEL_PENTIUM` (line 4742)
- `PROCESSOR_INTEL_IA64` (line 4743)
- `PROCESSOR_AMD_X8664` (line 4744)
- `PROCESSOR_MIPS_R4000` (line 4745)
- `PROCESSOR_ALPHA_21064` (line 4746)
- `PROCESSOR_PPC_601` (line 4747)
- `PROCESSOR_PPC_603` (line 4748)
- `PROCESSOR_PPC_604` (line 4749)
- `PROCESSOR_PPC_620` (line 4750)
- `PROCESSOR_HITACHI_SH3` (line 4751)
- `PROCESSOR_HITACHI_SH3E` (line 4752)
- `PROCESSOR_HITACHI_SH4` (line 4753)
- `PROCESSOR_MOTOROLA_821` (line 4754)
- `PROCESSOR_SHx_SH3` (line 4755)
- `PROCESSOR_SHx_SH4` (line 4756)
- `PROCESSOR_STRONGARM` (line 4757)
- `PROCESSOR_ARM720` (line 4758)
- `PROCESSOR_ARM820` (line 4759)
- `PROCESSOR_ARM920` (line 4760)
- `PROCESSOR_ARM_7TDMI` (line 4761)
- `PROCESSOR_OPTIL` (line 4762)
- `PROCESSOR_ARCHITECTURE_INTEL` (line 4763)
- `PROCESSOR_ARCHITECTURE_MIPS` (line 4765)
- `PROCESSOR_ARCHITECTURE_ALPHA` (line 4766)
- `PROCESSOR_ARCHITECTURE_PPC` (line 4767)
- `PROCESSOR_ARCHITECTURE_SHX` (line 4768)
- `PROCESSOR_ARCHITECTURE_ARM` (line 4769)
- `PROCESSOR_ARCHITECTURE_IA64` (line 4770)
- `PROCESSOR_ARCHITECTURE_ALPHA64` (line 4771)
- `PROCESSOR_ARCHITECTURE_MSIL` (line 4772)
- `PROCESSOR_ARCHITECTURE_AMD64` (line 4773)
- `PROCESSOR_ARCHITECTURE_IA32_ON_WIN64` (line 4774)
- `PROCESSOR_ARCHITECTURE_UNKNOWN` (line 4775)
- `PF_FLOATING_POINT_PRECISION_ERRATA` (line 4777)
- `PF_FLOATING_POINT_EMULATED` (line 4779)
- `PF_COMPARE_EXCHANGE_DOUBLE` (line 4780)
- `PF_MMX_INSTRUCTIONS_AVAILABLE` (line 4781)
- `PF_PPC_MOVEMEM_64BIT_OK` (line 4782)
- `PF_ALPHA_BYTE_INSTRUCTIONS` (line 4783)
- `PF_XMMI_INSTRUCTIONS_AVAILABLE` (line 4784)
- `PF_3DNOW_INSTRUCTIONS_AVAILABLE` (line 4785)
- `PF_RDTSC_INSTRUCTION_AVAILABLE` (line 4786)
- `PF_PAE_ENABLED` (line 4787)
- `PF_XMMI64_INSTRUCTIONS_AVAILABLE` (line 4788)
- `PF_SSE_DAZ_MODE_AVAILABLE` (line 4789)
- `PF_NX_ENABLED` (line 4790)
- `PF_SSE3_INSTRUCTIONS_AVAILABLE` (line 4791)
- `PF_COMPARE_EXCHANGE128` (line 4792)
- `PF_COMPARE64_EXCHANGE128` (line 4793)
- `PF_CHANNELS_ENABLED` (line 4794)
- `MM_WORKING_SET_MAX_HARD_ENABLE` (line 5064)
- `MM_WORKING_SET_MAX_HARD_DISABLE` (line 5066)
- `MM_WORKING_SET_MIN_HARD_ENABLE` (line 5067)
- `MM_WORKING_SET_MIN_HARD_DISABLE` (line 5068)
- `FLG_HOTPATCH_KERNEL` (line 5081)
- `FLG_HOTPATCH_RELOAD_NTDLL` (line 5083)
- `FLG_HOTPATCH_NAME_INFO` (line 5084)
- `FLG_HOTPATCH_RENAME_INFO` (line 5085)
- `FLG_HOTPATCH_MAP_ATOMIC_SWAP` (line 5086)
- `FLG_HOTPATCH_WOW64` (line 5087)
- `FLG_HOTPATCH_ACTIVE` (line 5088)
- `FLG_HOTPATCH_STATUS_FLAGS` (line 5090)
- `FLG_HOTPATCH_VERIFICATION_ERROR` (line 5091)
- `WDSTATE_FIRED` (line 5198)
- `WDSTATE_HARDWARE_ENABLED` (line 5200)
- `WDSTATE_STARTED` (line 5201)
- `WDSTATE_HARDWARE_PRESENT` (line 5202)
- `GDI_MAX_HANDLE_COUNT` (line 5208)
- `GDI_HANDLE_INDEX_SHIFT` (line 5210)
- `GDI_HANDLE_INDEX_BITS` (line 5212)
- `GDI_HANDLE_INDEX_MASK` (line 5213)
- `GDI_HANDLE_TYPE_SHIFT` (line 5214)
- `GDI_HANDLE_TYPE_BITS` (line 5216)
- `GDI_HANDLE_TYPE_MASK` (line 5217)
- `GDI_HANDLE_ALTTYPE_SHIFT` (line 5218)
- `GDI_HANDLE_ALTTYPE_BITS` (line 5220)
- `GDI_HANDLE_ALTTYPE_MASK` (line 5221)
- `GDI_HANDLE_STOCK_SHIFT` (line 5222)
- `GDI_HANDLE_STOCK_BITS` (line 5224)
- `GDI_HANDLE_STOCK_MASK` (line 5225)
- `GDI_HANDLE_UNIQUE_SHIFT` (line 5226)
- `GDI_HANDLE_UNIQUE_BITS` (line 5228)
- `GDI_HANDLE_UNIQUE_MASK` (line 5229)
- `GDI_HANDLE_INDEX` (line 5230)
- `GDI_HANDLE_TYPE` (line 5232)
- `GDI_HANDLE_ALTTYPE` (line 5233)
- `GDI_HANDLE_STOCK` (line 5234)
- `GDI_MAKE_HANDLE` (line 5235)
- `GDI_DEF_TYPE` (line 5239)
- `GDI_DC_TYPE` (line 5241)
- `GDI_DD_DIRECTDRAW_TYPE` (line 5242)
- `GDI_DD_SURFACE_TYPE` (line 5243)
- `GDI_RGN_TYPE` (line 5244)
- `GDI_SURF_TYPE` (line 5245)
- `GDI_CLIENTOBJ_TYPE` (line 5246)
- `GDI_PATH_TYPE` (line 5247)
- `GDI_PAL_TYPE` (line 5248)
- `GDI_ICMLCS_TYPE` (line 5249)
- `GDI_LFONT_TYPE` (line 5250)
- `GDI_RFONT_TYPE` (line 5251)
- `GDI_PFE_TYPE` (line 5252)
- `GDI_PFT_TYPE` (line 5253)
- `GDI_ICMCXF_TYPE` (line 5254)
- `GDI_ICMDLL_TYPE` (line 5255)
- `GDI_BRUSH_TYPE` (line 5256)
- `GDI_PFF_TYPE` (line 5257)
- `GDI_CACHE_TYPE` (line 5258)
- `GDI_SPACE_TYPE` (line 5259)
- `GDI_DBRUSH_TYPE` (line 5260)
- `GDI_META_TYPE` (line 5261)
- `GDI_EFSTATE_TYPE` (line 5262)
- `GDI_BMFD_TYPE` (line 5263)
- `GDI_VTFD_TYPE` (line 5264)
- `GDI_TTFD_TYPE` (line 5265)
- `GDI_RC_TYPE` (line 5266)
- `GDI_TEMP_TYPE` (line 5267)
- `GDI_DRVOBJ_TYPE` (line 5268)
- `GDI_DCIOBJ_TYPE` (line 5269)
- `GDI_SPOOL_TYPE` (line 5270)
- `GDI_CLIENT_TYPE_FROM_HANDLE` (line 5273)
- `GDI_CLIENT_TYPE_FROM_UNIQUE` (line 5276)
- `GDI_ALTTYPE_1` (line 5277)
- `GDI_ALTTYPE_2` (line 5279)
- `GDI_ALTTYPE_3` (line 5280)
- `GDI_CLIENT_BITMAP_TYPE` (line 5281)
- `GDI_CLIENT_BRUSH_TYPE` (line 5283)
- `GDI_CLIENT_CLIENTOBJ_TYPE` (line 5284)
- `GDI_CLIENT_DC_TYPE` (line 5285)
- `GDI_CLIENT_FONT_TYPE` (line 5286)
- `GDI_CLIENT_PALETTE_TYPE` (line 5287)
- `GDI_CLIENT_REGION_TYPE` (line 5288)
- `GDI_CLIENT_ALTDC_TYPE` (line 5289)
- `GDI_CLIENT_DIBSECTION_TYPE` (line 5291)
- `GDI_CLIENT_EXTPEN_TYPE` (line 5292)
- `GDI_CLIENT_METADC16_TYPE` (line 5293)
- `GDI_CLIENT_METAFILE_TYPE` (line 5294)
- `GDI_CLIENT_METAFILE16_TYPE` (line 5295)
- `GDI_CLIENT_PEN_TYPE` (line 5296)
- `FLS_MAXIMUM_AVAILABLE` (line 5325)
- `TLS_MINIMUM_AVAILABLE` (line 5327)
- `TLS_EXPANSION_SLOTS` (line 5328)
- `DOS_MAX_COMPONENT_LENGTH` (line 5329)
- `DOS_MAX_PATH_LENGTH` (line 5331)
- `RTL_USER_PROC_CURDIR_CLOSE` (line 5338)
- `RTL_USER_PROC_CURDIR_INHERIT` (line 5340)
- `RTL_MAX_DRIVE_LETTERS` (line 5349)
- `RTL_DRIVE_LETTER_VALID` (line 5351)
- `WOW64_SYSTEM_DIRECTORY` (line 5392)
- `WOW64_SYSTEM_DIRECTORY_U` (line 5394)
- `WOW64_X86_TAG` (line 5395)
- `WOW64_X86_TAG_U` (line 5396)
- `SET_LAST_STATUS` (line 5416)
- `WOW64_POINTER` (line 5434)
- `LDR_DATA_TABLE_ENTRY_SIZE_WINXP32` (line 5449)
- `GDI_BATCH_BUFFER_SIZE` (line 5641)
- `PORT_CONNECT` (line 5839)
- `PORT_ALL_ACCESS` (line 5841)
- `CSR_API_PORT_NAME` (line 5897)
- `CSR_NORMAL_PRIORITY_CLASS` (line 5928)
- `CSR_IDLE_PRIORITY_CLASS` (line 5930)
- `CSR_HIGH_PRIORITY_CLASS` (line 5931)
- `CSR_REALTIME_PRIORITY_CLASS` (line 5932)
- `WINSS_OBJECT_DIRECTORY_NAME` (line 5941)
- `CSRSRV_SERVERDLL_INDEX` (line 5943)
- `CSRSRV_FIRST_API_NUMBER` (line 5945)
- `BASESRV_SERVERDLL_INDEX` (line 5946)
- `BASESRV_FIRST_API_NUMBER` (line 5948)
- `CONSRV_SERVERDLL_INDEX` (line 5949)
- `CONSRV_FIRST_API_NUMBER` (line 5951)
- `USERSRV_SERVERDLL_INDEX` (line 5952)
- `USERSRV_FIRST_API_NUMBER` (line 5954)
- `CSR_MAKE_API_NUMBER` (line 5955)
- `CSR_APINUMBER_TO_SERVERDLLINDEX` (line 5958)
- `CSR_APINUMBER_TO_APITABLEINDEX` (line 5961)
- `GDI_BATCH_BUFFER_SIZE` (line 6439)
- `STATIC_UNICODE_BUFFER_LENGTH` (line 6463)
- `WIN32_CLIENT_INFO_LENGTH` (line 6465)
- `WIN32_CLIENT_INFO_SPIN_COUNT` (line 6466)
- `TLS_MINIMUM_AVAILABLE` (line 6470)
- `LDRP_STATIC_LINK` (line 6555)
- `LDRP_IMAGE_DLL` (line 6557)
- `LDRP_LOAD_IN_PROGRESS` (line 6558)
- `LDRP_UNLOAD_IN_PROGRESS` (line 6559)
- `LDRP_ENTRY_PROCESSED` (line 6560)
- `LDRP_ENTRY_INSERTED` (line 6561)
- `LDRP_CURRENT_LOAD` (line 6562)
- `LDRP_FAILED_BUILTIN_LOAD` (line 6563)
- `LDRP_DONT_CALL_FOR_THREADS` (line 6564)
- `LDRP_PROCESS_ATTACH_CALLED` (line 6565)
- `LDRP_DEBUG_SYMBOLS_LOADED` (line 6566)
- `LDRP_IMAGE_NOT_AT_BASE` (line 6567)
- `LDRP_COR_IMAGE` (line 6568)
- `LDRP_COR_OWNS_UNMAP` (line 6569)
- `LDRP_SYSTEM_MAPPED` (line 6570)
- `LDRP_IMAGE_VERIFYING` (line 6571)
- `LDRP_DRIVER_DEPENDENT_DLL` (line 6572)
- `LDRP_ENTRY_NATIVE` (line 6573)
- `LDRP_REDIRECTED` (line 6574)
- `LDRP_NON_PAGED_DEBUG_INFO` (line 6575)
- `LDRP_MM_LOADED` (line 6576)
- `LDRP_COMPAT_DATABASE_PROCESSED` (line 6577)
- `LDR_GET_DLL_HANDLE_EX_UNCHANGED_REFCOUNT` (line 6578)
- `LDR_GET_DLL_HANDLE_EX_PIN` (line 6580)
- `LDR_ADDREF_DLL_PIN` (line 6581)
- `LDR_GET_PROCEDURE_ADDRESS_DONT_RECORD_FORWARDER` (line 6583)
- `LDR_LOCK_LOADER_LOCK_FLAG_RAISE_ON_ERRORS` (line 6585)
- `LDR_LOCK_LOADER_LOCK_FLAG_TRY_ONLY` (line 6587)
- `LDR_LOCK_LOADER_LOCK_DISPOSITION_INVALID` (line 6588)
- `LDR_LOCK_LOADER_LOCK_DISPOSITION_LOCK_ACQUIRED` (line 6590)
- `LDR_LOCK_LOADER_LOCK_DISPOSITION_LOCK_NOT_ACQUIRED` (line 6591)
- `LDR_UNLOCK_LOADER_LOCK_FLAG_RAISE_ON_ERRORS` (line 6592)
- `LDR_DLL_NOTIFICATION_REASON_LOADED` (line 6594)
- `LDR_DLL_NOTIFICATION_REASON_UNLOADED` (line 6596)
- `DOS_MAX_COMPONENT_LENGTH` (line 6719)
- `DOS_MAX_PATH_LENGTH` (line 6721)
- `RTL_USER_PROC_CURDIR_CLOSE` (line 6722)
- `RTL_USER_PROC_CURDIR_INHERIT` (line 6724)
- `RTL_MAX_DRIVE_LETTERS` (line 6752)
- `RTL_DRIVE_LETTER_VALID` (line 6754)
- `ACTIVATION_CONTEXT_STACK_FLAG_QUERIES_DISABLED` (line 6892)
- `TEB_ACTIVE_FRAME_CONTEXT_FLAG_EXTENDED` (line 6913)
- `TEB_ACTIVE_FRAME_FLAG_EXTENDED` (line 6931)
- `PcTeb` (line 7095)
- `RtlGetCurrentProcessId` (line 7097)
- `RtlGetCurrentThreadId` (line 7099)
- `ZwCurrentProcess` (line 7100)
- `WOWAddress` (line 7105)
- `RtlProcessHeap` (line 7106)
- `RtlAcquireLockRoutine` (line 7109)
- `RTL_HEAP_BUSY` (line 7202)
- `RTL_HEAP_SEGMENT` (line 7204)
- `RTL_HEAP_SETTABLE_VALUE` (line 7205)
- `RTL_HEAP_SETTABLE_FLAG1` (line 7206)
- `RTL_HEAP_SETTABLE_FLAG2` (line 7207)
- `RTL_HEAP_SETTABLE_FLAG3` (line 7208)
- `RTL_HEAP_SETTABLE_FLAGS` (line 7209)
- `RTL_HEAP_UNCOMMITTED_RANGE` (line 7210)
- `RTL_HEAP_PROTECTED_ENTRY` (line 7211)
- `POINTER_64` (line 7302)
- `POINTER_32` (line 7305)
- `POINTER_32` (line 7307)
- `VER_SERVER_NT` (line 7338)
- `VER_WORKSTATION_NT` (line 7340)
- `VER_SUITE_SMALLBUSINESS` (line 7341)
- `VER_SUITE_ENTERPRISE` (line 7342)
- `VER_SUITE_BACKOFFICE` (line 7343)
- `VER_SUITE_COMMUNICATIONS` (line 7344)
- `VER_SUITE_TERMINAL` (line 7345)
- `VER_SUITE_SMALLBUSINESS_RESTRICTED` (line 7346)
- `VER_SUITE_EMBEDDEDNT` (line 7347)
- `VER_SUITE_DATACENTER` (line 7348)
- `VER_SUITE_SINGLEUSERTS` (line 7349)
- `VER_SUITE_PERSONAL` (line 7350)
- `VER_SUITE_BLADE` (line 7351)
- `VER_SUITE_EMBEDDED_RESTRICTED` (line 7352)
- `VER_SUITE_SECURITY_APPLIANCE` (line 7353)
- `VER_SUITE_STORAGE_SERVER` (line 7354)
- `VER_SUITE_COMPUTE_SERVER` (line 7355)
- `EXCEPTION_CHAIN_END` (line 7516)
- `MAJOR_VERSION` (line 7518)
- `MINOR_VERSION` (line 7520)
- `OS2_VERSION` (line 7521)
- `DBG_TEB_THREADNAME` (line 7524)
- `DBG_TEB_RESERVED_1` (line 7525)
- `DBG_TEB_RESERVED_2` (line 7526)
- `DBG_TEB_RESERVED_3` (line 7527)
- `DBG_TEB_RESERVED_4` (line 7528)
- `DBG_TEB_RESERVED_5` (line 7529)
- `DBG_TEB_RESERVED_6` (line 7530)
- `DBG_TEB_RESERVED_7` (line 7531)
- `DBG_TEB_RESERVED_8` (line 7532)
- `PROCESS_PRIORITY_CLASS_UNKNOWN` (line 7534)
- `PROCESS_PRIORITY_CLASS_IDLE` (line 7536)
- `PROCESS_PRIORITY_CLASS_NORMAL` (line 7537)
- `PROCESS_PRIORITY_CLASS_HIGH` (line 7538)
- `PROCESS_PRIORITY_CLASS_REALTIME` (line 7539)
- `PROCESS_PRIORITY_CLASS_BELOW_NORMAL` (line 7540)
- `PROCESS_PRIORITY_CLASS_ABOVE_NORMAL` (line 7541)
- `FILE_PATH_VERSION` (line 7558)
- `FILE_PATH_TYPE_ARC` (line 7560)
- `FILE_PATH_TYPE_ARC_SIGNATURE` (line 7562)
- `FILE_PATH_TYPE_NT` (line 7563)
- `FILE_PATH_TYPE_EFI` (line 7564)
- `FILE_PATH_TYPE_MIN` (line 7565)
- `FILE_PATH_TYPE_MAX` (line 7567)
- `WINDOWS_OS_OPTIONS_SIGNATURE` (line 7577)
- `WINDOWS_OS_OPTIONS_VERSION` (line 7579)
- `LongAlignPtr` (line 7626)
- `LongAlignSize` (line 7628)
- `RtlpOwnerAddrSecurityDescriptor` (line 7637)
- `RtlpGroupAddrSecurityDescriptor` (line 7645)
- `RtlpSaclAddrSecurityDescriptor` (line 7653)
- `RtlpDaclAddrSecurityDescriptor` (line 7664)
- `RtlpIdAssignableAsOwner` (line 7682)
- `RtlpPropagateControlBits` (line 7691)
- `RtlpAreControlBitsSet` (line 7703)
- `RtlpSetControlBits` (line 7713)
- `RtlpClearControlBits` (line 7722)
- `Audit_System_SecurityStateChange_defined` (line 7743)
- `Audit_System_SecuritySubsystemExtension_defined` (line 7755)
- `Audit_System_Integrity_defined` (line 7767)
- `Audit_System_IPSecDriverEvents_defined` (line 7779)
- `Audit_System_Others_defined` (line 7791)
- `Audit_Logon_Logon_defined` (line 7803)
- `Audit_Logon_Logoff_defined` (line 7815)
- `Audit_Logon_AccountLockout_defined` (line 7827)
- `Audit_Logon_IPSecMainMode_defined` (line 7839)
- `Audit_Logon_IPSecQuickMode_defined` (line 7851)
- `Audit_Logon_IPSecUserMode_defined` (line 7863)
- `Audit_Logon_SpecialLogon_defined` (line 7875)
- `Audit_Logon_Others_defined` (line 7887)
- `Audit_ObjectAccess_FileSystem_defined` (line 7899)
- `Audit_ObjectAccess_Registry_defined` (line 7911)
- `Audit_ObjectAccess_Kernel_defined` (line 7923)
- `Audit_ObjectAccess_Sam_defined` (line 7935)
- `Audit_ObjectAccess_CertificationServices_defined` (line 7947)
- `Audit_ObjectAccess_ApplicationGenerated_defined` (line 7959)
- `Audit_ObjectAccess_Handle_defined` (line 7979)
- `Audit_ObjectAccess_Share_defined` (line 7991)
- `Audit_ObjectAccess_FirewallPacketDrops_defined` (line 8003)
- `Audit_ObjectAccess_FirewallConnection_defined` (line 8015)
- `Audit_ObjectAccess_Other_defined` (line 8027)
- `Audit_PrivilegeUse_Sensitive_defined` (line 8039)
- `Audit_PrivilegeUse_NonSensitive_defined` (line 8051)
- `Audit_PrivilegeUse_Others_defined` (line 8063)
- `Audit_DetailedTracking_ProcessCreation_defined` (line 8075)
- `Audit_DetailedTracking_ProcessTermination_defined` (line 8087)
- `Audit_DetailedTracking_DpapiActivity_defined` (line 8099)
- `Audit_DetailedTracking_RpcCall_defined` (line 8111)
- `Audit_PolicyChange_AuditPolicy_defined` (line 8123)
- `Audit_PolicyChange_AuthenticationPolicy_defined` (line 8135)
- `Audit_PolicyChange_AuthorizationPolicy_defined` (line 8147)
- `Audit_PolicyChange_MpsscvRulePolicy_defined` (line 8159)
- `Audit_PolicyChange_WfpIPSecPolicy_defined` (line 8171)
- `Audit_PolicyChange_Others_defined` (line 8183)
- `Audit_AccountManagement_UserAccount_defined` (line 8195)
- `Audit_AccountManagement_ComputerAccount_defined` (line 8207)
- `Audit_AccountManagement_SecurityGroup_defined` (line 8219)
- `Audit_AccountManagement_DistributionGroup_defined` (line 8231)
- `Audit_AccountManagement_ApplicationGroup_defined` (line 8243)
- `Audit_AccountManagement_Others_defined` (line 8255)
- `Audit_DSAccess_DSAccess_defined` (line 8267)
- `Audit_DsAccess_AdAuditChanges_defined` (line 8279)
- `Audit_Ds_Replication_defined` (line 8291)
- `Audit_Ds_DetailedReplication_defined` (line 8303)
- `Audit_AccountLogon_CredentialValidation_defined` (line 8315)
- `Audit_AccountLogon_Kerberos_defined` (line 8327)
- `Audit_AccountLogon_Others_defined` (line 8339)
- `Audit_AccountLogon_KerbCredentialValidation_defined` (line 8351)
- `Audit_Logon_NPS_defined` (line 8363)
- `Audit_ObjectAccess_DetailedFileShare_defined` (line 8375)
- `Audit_System_defined` (line 8396)
- `Audit_Logon_defined` (line 8408)
- `Audit_ObjectAccess_defined` (line 8420)
- `Audit_PrivilegeUse_defined` (line 8432)
- `Audit_DetailedTracking_defined` (line 8444)
- `Audit_PolicyChange_defined` (line 8456)
- `Audit_AccountManagement_defined` (line 8468)
- `Audit_DirectoryServiceAccess_defined` (line 8480)
- `Audit_AccountLogon_defined` (line 8492)
- `_NTLSA_IFS_` (line 8500)
- `_LSALOOKUP_` (line 8503)
- `LOOKUP_VIEW_LOCAL_INFORMATION` (line 8577)
- `LOOKUP_TRANSLATE_NAMES` (line 8579)
- `LSA_MODE_PASSWORD_PROTECTED` (line 8634)
- `LSA_MODE_INDIVIDUAL_ACCOUNTS` (line 8636)
- `LSA_MODE_MANDATORY_ACCESS` (line 8637)
- `LSA_MODE_LOG_FULL` (line 8638)
- `_NTLSA_AUDIT_` (line 8665)
- `SE_ADT_OBJECT_ONLY` (line 8718)
- `SE_MAX_AUDIT_PARAMETERS` (line 8739)
- `SE_MAX_GENERIC_AUDIT_PARAMETERS` (line 8741)
- `SE_ADT_PARAMETERS_SELF_RELATIVE` (line 8755)
- `SE_ADT_PARAMETERS_SEND_TO_LSA` (line 8757)
- `SE_ADT_PARAMETER_EXTENSIBLE_AUDIT` (line 8758)
- `SE_ADT_PARAMETER_GENERIC_AUDIT` (line 8759)
- `SE_ADT_PARAMETER_WRITE_SYNCHRONOUS` (line 8760)
- `LSAP_SE_ADT_PARAMETER_ARRAY_TRUE_SIZE` (line 8761)
- `POLICY_AUDIT_EVENT_UNCHANGED` (line 8782)
- `POLICY_AUDIT_EVENT_SUCCESS` (line 8784)
- `POLICY_AUDIT_EVENT_FAILURE` (line 8785)
- `POLICY_AUDIT_EVENT_NONE` (line 8786)
- `POLICY_AUDIT_EVENT_MASK` (line 8787)
- `LSA_SUCCESS` (line 8793)
- `POLICY_VIEW_LOCAL_INFORMATION` (line 8866)
- `POLICY_VIEW_AUDIT_INFORMATION` (line 8868)
- `POLICY_GET_PRIVATE_INFORMATION` (line 8869)
- `POLICY_TRUST_ADMIN` (line 8870)
- `POLICY_CREATE_ACCOUNT` (line 8871)
- `POLICY_CREATE_SECRET` (line 8872)
- `POLICY_CREATE_PRIVILEGE` (line 8873)
- `POLICY_SET_DEFAULT_QUOTA_LIMITS` (line 8874)
- `POLICY_SET_AUDIT_REQUIREMENTS` (line 8875)
- `POLICY_AUDIT_LOG_ADMIN` (line 8876)
- `POLICY_SERVER_ADMIN` (line 8877)
- `POLICY_LOOKUP_NAMES` (line 8878)
- `POLICY_NOTIFICATION` (line 8879)
- `POLICY_ALL_ACCESS` (line 8880)
- `POLICY_READ` (line 8894)
- `POLICY_WRITE` (line 8899)
- `POLICY_EXECUTE` (line 8909)
- `PER_USER_POLICY_UNCHANGED` (line 8997)
- `PER_USER_AUDIT_SUCCESS_INCLUDE` (line 8999)
- `PER_USER_AUDIT_SUCCESS_EXCLUDE` (line 9000)
- `PER_USER_AUDIT_FAILURE_INCLUDE` (line 9001)
- `PER_USER_AUDIT_FAILURE_EXCLUDE` (line 9002)
- `PER_USER_AUDIT_NONE` (line 9003)
- `VALID_PER_USER_AUDIT_POLICY_FLAG` (line 9004)
- `POLICY_QOS_SCHANNEL_REQUIRED` (line 9079)
- `POLICY_QOS_OUTBOUND_INTEGRITY` (line 9081)
- `POLICY_QOS_OUTBOUND_CONFIDENTIALITY` (line 9082)
- `POLICY_QOS_INBOUND_INTEGRITY` (line 9083)
- `POLICY_QOS_INBOUND_CONFIDENTIALITY` (line 9084)
- `POLICY_QOS_ALLOW_LOCAL_ROOT_CERT_STORE` (line 9085)
- `POLICY_QOS_RAS_SERVER_ALLOWED` (line 9086)
- `POLICY_QOS_DHCP_SERVER_ALLOWED` (line 9087)
- `POLICY_KERBEROS_VALIDATE_CLIENT` (line 9109)
- `TRUST_DIRECTION_DISABLED` (line 9181)
- `TRUST_DIRECTION_INBOUND` (line 9183)
- `TRUST_DIRECTION_OUTBOUND` (line 9184)
- `TRUST_DIRECTION_BIDIRECTIONAL` (line 9185)
- `TRUST_TYPE_DOWNLEVEL` (line 9186)
- `TRUST_TYPE_UPLEVEL` (line 9188)
- `TRUST_TYPE_MIT` (line 9189)
- `TRUST_TYPE_DCE` (line 9192)
- `TRUST_ATTRIBUTE_NON_TRANSITIVE` (line 9197)
- `TRUST_ATTRIBUTE_UPLEVEL_ONLY` (line 9199)
- `TRUST_ATTRIBUTE_TREE_PARENT` (line 9201)
- `TRUST_ATTRIBUTE_TREE_ROOT` (line 9203)
- `TRUST_ATTRIBUTES_VALID` (line 9208)
- `TRUST_ATTRIBUTE_FILTER_SIDS` (line 9212)
- `TRUST_ATTRIBUTE_QUARANTINED_DOMAIN` (line 9214)
- `TRUST_ATTRIBUTE_FOREST_TRANSITIVE` (line 9218)
- `TRUST_ATTRIBUTE_CROSS_ORGANIZATION` (line 9220)
- `TRUST_ATTRIBUTE_WITHIN_FOREST` (line 9221)
- `TRUST_ATTRIBUTE_TREAT_AS_EXTERNAL` (line 9222)
- `TRUST_ATTRIBUTE_TRUST_USES_RC4_ENCRYPTION` (line 9224)
- `TRUST_ATTRIBUTE_TRUST_USES_AES_KEYS` (line 9225)
- `TRUST_ATTRIBUTES_VALID` (line 9233)
- `TRUST_ATTRIBUTES_USER` (line 9235)
- `TRUST_AUTH_TYPE_NONE` (line 9263)
- `TRUST_AUTH_TYPE_NT4OWF` (line 9265)
- `TRUST_AUTH_TYPE_CLEAR` (line 9266)
- `TRUST_AUTH_TYPE_VERSION` (line 9267)
- `LSA_FOREST_TRUST_RECORD_TYPE_UNRECOGNIZED` (line 9320)
- `LSA_FTRECORD_DISABLED_REASONS` (line 9326)
- `LSA_TLN_DISABLED_NEW` (line 9332)
- `LSA_TLN_DISABLED_ADMIN` (line 9334)
- `LSA_TLN_DISABLED_CONFLICT` (line 9335)
- `LSA_SID_DISABLED_ADMIN` (line 9340)
- `LSA_SID_DISABLED_CONFLICT` (line 9342)
- `LSA_NB_DISABLED_ADMIN` (line 9343)
- `LSA_NB_DISABLED_CONFLICT` (line 9344)
- `MAX_FOREST_TRUST_BINARY_DATA_SIZE` (line 9364)
- `MAX_RECORDS_IN_FOREST_TRUST_INFO` (line 9411)
- `SE_INTERACTIVE_LOGON_NAME` (line 9649)
- `SE_NETWORK_LOGON_NAME` (line 9651)
- `SE_BATCH_LOGON_NAME` (line 9652)
- `SE_SERVICE_LOGON_NAME` (line 9653)
- `SE_DENY_INTERACTIVE_LOGON_NAME` (line 9654)
- `SE_DENY_NETWORK_LOGON_NAME` (line 9655)
- `SE_DENY_BATCH_LOGON_NAME` (line 9656)
- `SE_DENY_SERVICE_LOGON_NAME` (line 9657)
- `SE_REMOTE_INTERACTIVE_LOGON_NAME` (line 9659)
- `SE_DENY_REMOTE_INTERACTIVE_LOGON_NAME` (line 9660)
- `EFI_DRIVER_ENTRY_VERSION` (line 9868)
- `MAX_STACK_DEPTH` (line 9870)
- `HEAP_SETTABLE_USER_VALUE` (line 9903)
- `HEAP_SETTABLE_USER_FLAG1` (line 9905)
- `HEAP_SETTABLE_USER_FLAG2` (line 9906)
- `HEAP_SETTABLE_USER_FLAG3` (line 9907)
- `HEAP_SETTABLE_USER_FLAGS` (line 9908)
- `HEAP_CLASS_0` (line 9909)
- `HEAP_CLASS_1` (line 9911)
- `HEAP_CLASS_2` (line 9912)
- `HEAP_CLASS_3` (line 9913)
- `HEAP_CLASS_4` (line 9914)
- `HEAP_CLASS_5` (line 9915)
- `HEAP_CLASS_6` (line 9916)
- `HEAP_CLASS_7` (line 9917)
- `HEAP_CLASS_8` (line 9918)
- `HEAP_CLASS_MASK` (line 9919)
- `COMPRESSION_FORMAT_NONE` (line 10101)
- `COMPRESSION_FORMAT_DEFAULT` (line 10103)
- `COMPRESSION_FORMAT_LZNT1` (line 10104)
- `COMPRESSION_ENGINE_STANDARD` (line 10105)
- `COMPRESSION_ENGINE_MAXIMUM` (line 10107)
- `COMPRESSION_ENGINE_HIBER` (line 10108)
- `RTL_USER_PROC_CURDIR_CLOSE` (line 10191)
- `RTL_USER_PROC_CURDIR_INHERIT` (line 10193)
- `RTL_RANGE_SHARED` (line 10194)
- `RTL_RANGE_CONFLICT` (line 10196)
- `RTL_USER_PROC_PARAMS_NORMALIZED` (line 10228)
- `RTL_USER_PROC_PROFILE_USER` (line 10230)
- `RTL_USER_PROC_PROFILE_KERNEL` (line 10231)
- `RTL_USER_PROC_PROFILE_SERVER` (line 10232)
- `RTL_USER_PROC_RESERVE_1MB` (line 10233)
- `RTL_USER_PROC_RESERVE_16MB` (line 10234)
- `RTL_USER_PROC_CASE_SENSITIVE` (line 10235)
- `RTL_USER_PROC_DISABLE_HEAP_DECOMMIT` (line 10236)
- `RTL_USER_PROC_DLL_REDIRECTION_LOCAL` (line 10237)
- `RTL_USER_PROC_APP_MANIFEST_PRESENT` (line 10238)
- `RTL_USER_PROC_IMAGE_KEY_MISSING` (line 10239)
- `RTL_USER_PROC_OPTIN_PROCESS` (line 10240)
- `RTL_TRACE_IN_USER_MODE` (line 10265)
- `RTL_TRACE_IN_KERNEL_MODE` (line 10267)
- `RTL_TRACE_USE_NONPAGED_POOL` (line 10268)
- `RTL_TRACE_USE_PAGED_POOL` (line 10269)
- `RTL_RESOURCE_FLAG_LONG_TERM` (line 10287)
- `RTL_HEAP_BUSY` (line 10334)
- `RTL_HEAP_SEGMENT` (line 10336)
- `RTL_HEAP_SETTABLE_VALUE` (line 10337)
- `RTL_HEAP_SETTABLE_FLAG1` (line 10338)
- `RTL_HEAP_SETTABLE_FLAG2` (line 10339)
- `RTL_HEAP_SETTABLE_FLAG3` (line 10340)
- `RTL_HEAP_SETTABLE_FLAGS` (line 10341)
- `RTL_HEAP_UNCOMMITTED_RANGE` (line 10342)
- `RTL_HEAP_PROTECTED_ENTRY` (line 10343)
- `SET_LAST_STATUS` (line 10420)
- `HEAP_GRANULARITY` (line 10422)
- `HEAP_GRANULARITY_SHIFT` (line 10424)
- `HEAP_MAXIMUM_BLOCK_SIZE` (line 10425)
- `HEAP_MAXIMUM_FREELISTS` (line 10427)
- `HEAP_MAXIMUM_SEGMENTS` (line 10429)
- `HEAP_ENTRY_BUSY` (line 10430)
- `HEAP_ENTRY_EXTRA_PRESENT` (line 10432)
- `HEAP_ENTRY_FILL_PATTERN` (line 10433)
- `HEAP_ENTRY_VIRTUAL_ALLOC` (line 10434)
- `HEAP_ENTRY_LAST_ENTRY` (line 10435)
- `HEAP_ENTRY_SETTABLE_FLAG1` (line 10436)
- `HEAP_ENTRY_SETTABLE_FLAG2` (line 10437)
- `HEAP_ENTRY_SETTABLE_FLAG3` (line 10438)
- `HEAP_ENTRY_SETTABLE_FLAGS` (line 10439)
- `NX_SUPPORT_POLICY_ALWAYSOFF` (line 10648)
- `NX_SUPPORT_POLICY_ALWAYSON` (line 10650)
- `NX_SUPPORT_POLICY_OPTIN` (line 10651)
- `NX_SUPPORT_POLICY_OPTOUT` (line 10652)
- `PROCESSOR_FEATURE_MAX` (line 10653)
- `MAX_WOW64_SHARED_ENTRIES` (line 10655)
- `XSTATE_LEGACY_FLOATING_POINT` (line 10658)
- `XSTATE_LEGACY_SSE` (line 10660)
- `XSTATE_GSSE` (line 10661)
- `XSTATE_MASK_LEGACY_FLOATING_POINT` (line 10662)
- `XSTATE_MASK_LEGACY_SSE` (line 10664)
- `XSTATE_MASK_LEGACY` (line 10665)
- `XSTATE_MASK_GSSE` (line 10666)
- `MAXIMUM_XSTATE_FEATURES` (line 10667)
- `SHARED_USER_DATA_VA` (line 10901)
- `USER_SHARED_DATA` (line 10903)
- `RTL_CLONE_PROCESS_FLAGS_CREATE_SUSPENDED` (line 10910)
- `RTL_CLONE_PROCESS_FLAGS_INHERIT_HANDLES` (line 10911)
- `RTL_CLONE_PROCESS_FLAGS_NO_SYNCHRONIZE` (line 10912)
- `SIZEOF_BP_BUFFER` (line 10973)
- `LPC_BUFFER_SIZE` (line 10975)
- `DEBUG_READ_EVENT` (line 11066)
- `DEBUG_PROCESS_ASSIGN` (line 11068)
- `DEBUG_SET_INFORMATION` (line 11069)
- `DEBUG_QUERY_INFORMATION` (line 11070)
- `DEBUG_ALL_ACCESS` (line 11071)
- `DEBUG_KILL_ON_CLOSE` (line 11074)
- `RTL_HEAP_MAKE_TAG` (line 11092)
- `MAKE_TAG` (line 11094)
- `HEAP_USAGE_ALLOCATED_BLOCKS` (line 11122)
- `HEAP_USAGE_FREE_BUFFER` (line 11124)
- `HeapDebuggingInformation` (line 11151)
- `PREALLOCATE_EVENT_MASK` (line 11175)
- `RtlInitializeLockRoutine` (line 11176)
- `RtlAcquireLockRoutine` (line 11178)
- `RtlReleaseLockRoutine` (line 11179)
- `RtlDeleteLockRoutine` (line 11180)
- `MAX_STACK_DEPTH` (line 11237)
- `RTL_HANDLE_ALLOCATED` (line 11338)
- `RTL_ATOM_MAXIMUM_INTEGER_ATOM` (line 11402)
- `RTL_ATOM_INVALID_ATOM` (line 11404)
- `RTL_ATOM_TABLE_DEFAULT_NUMBER_OF_BUCKETS` (line 11405)
- `RTL_ATOM_MAXIMUM_NAME_LENGTH` (line 11406)
- `RTL_ATOM_PINNED` (line 11407)
- `EVENT_MIN_LEVEL` (line 11485)
- `EVENT_MAX_LEVEL` (line 11487)
- `EVENT_ACTIVITY_CTRL_GET_ID` (line 11488)
- `EVENT_ACTIVITY_CTRL_SET_ID` (line 11490)
- `EVENT_ACTIVITY_CTRL_CREATE_ID` (line 11491)
- `EVENT_ACTIVITY_CTRL_GET_SET_ID` (line 11492)
- `EVENT_ACTIVITY_CTRL_CREATE_SET_ID` (line 11493)
- `MAX_EVENT_DATA_DESCRIPTORS` (line 11496)
- `MAX_EVENT_FILTER_DATA_SIZE` (line 11498)
- `_SLIST_HEADER_` (line 11616)
- `SLIST_ENTRY` (line 11638)
- `_SLIST_ENTRY` (line 11640)
- `PSLIST_ENTRY` (line 11641)
- `RTL_UNLOAD_EVENT_TRACE_NUMBER` (line 21426)
- `RtlEqualMemory` (line 21674)
- `RtlMoveMemory` (line 21676)
- `RtlCopyMemory` (line 21677)
- `RtlFillMemory` (line 21678)
- `RtlZeroMemory` (line 21679)

**Structs:**
- `_STRING` (line 366)
- `_CSTRING` (line 382)
- `_UNICODE_STRING` (line 394)
- `_STRING32` (line 402)
- `_STRING64` (line 417)
- `_LIST_ENTRY` (line 444)
- `_TRIPLE_LIST_ENTRY` (line 456)
- `_OBJECT_ATTRIBUTES` (line 505)
- `_OBJECT_DIRECTORY_INFORMATION` (line 527) - *added 20.12.11*
- `_PROCESSOR_NUMBER` (line 534) - *if defined(_WINNT_) && (_MSC_VER < 1300) && !defined(___PROCESSOR_NUMBER_DEFINED) define ___PROCESSOR_NUMBER_DEFINED*
- `_CSV_NAMESPACE_INFO` (line 888)
- `_PATHNAME_BUFFER` (line 902)
- `_FSCTL_QUERY_FAT_BPB_BUFFER` (line 909)
- `RETRIEVAL_POINTERS_BUFFER` (line 971)
- `_MOVE_FILE_DATA32` (line 1022)
- `_FILE_PREFETCH` (line 1205)
- `_FILE_PREFETCH_EX` (line 1211)
- `_FILESYSTEM_STATISTICS` (line 1227)
- `_FAT_STATISTICS` (line 1254) - *define FILESYSTEM_STATISTICS_TYPE_NTFS     1 define FILESYSTEM_STATISTICS_TYPE_FAT      2 define FILESYSTEM_STATISTICS_TYPE_EXFAT    3*
- `_EXFAT_STATISTICS` (line 1268)
- `_NTFS_STATISTICS` (line 1282)
- `_FILE_OBJECTID_BUFFER` (line 1384)
- `_FILE_SET_SPARSE_BUFFER` (line 1410)
- `_FILE_ZERO_DATA_INFORMATION` (line 1421)
- `_FILE_ALLOCATED_RANGE_BUFFER` (line 1431)
- `_ENCRYPTION_BUFFER` (line 1442)
- `_DECRYPTION_STATUS_BUFFER` (line 1456)
- `_REQUEST_RAW_ENCRYPTED_DATA` (line 1466)
- `_ENCRYPTED_DATA_INFO` (line 1473)
- `_PLEX_READ_DATA_REQUEST` (line 1502)
- `_SI_COPYFILE` (line 1513)
- `_FILE_MAKE_COMPATIBLE_BUFFER` (line 1527)
- `_FILE_SET_DEFECT_MGMT_BUFFER` (line 1532)
- `_FILE_QUERY_SPARING_BUFFER` (line 1537)
- `_FILE_QUERY_ON_DISK_VOL_INFO_BUFFER` (line 1545)
- `_SHRINK_VOLUME_INFORMATION` (line 1575)
- `_TXFS_MODIFY_RM` (line 1628)
- `_TXFS_QUERY_RM_INFORMATION` (line 1700)
- `_TXFS_ROLLFORWARD_REDO_INFORMATION` (line 1802)
- `_TXFS_START_RM_INFORMATION` (line 1840)
- `_TXFS_GET_METADATA_INFO_OUT` (line 1930)
- `_TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY` (line 1964)
- `_TXFS_LIST_TRANSACTION_LOCKED_FILES` (line 2002)
- `_TXFS_LIST_TRANSACTIONS_ENTRY` (line 2035)
- `_TXFS_LIST_TRANSACTIONS` (line 2058)
- `_TXFS_READ_BACKUP_INFORMATION_OUT` (line 2081)
- `_TXFS_WRITE_BACKUP_INFORMATION` (line 2104)
- `_TXFS_GET_TRANSACTED_VERSION` (line 2111)
- `_TXFS_SAVEPOINT_INFORMATION` (line 2172)
- `_TXFS_CREATE_MINIVERSION_INFO` (line 2179)
- `_TXFS_TRANSACTION_ACTIVE_INFO` (line 2188)
- `_BOOT_AREA_INFO` (line 2197)
- `_RETRIEVAL_POINTER_BASE` (line 2206)
- `_FILE_FS_PERSISTENT_VOLUME_INFORMATION` (line 2211)
- `_FILE_SYSTEM_RECOGNITION_INFORMATION` (line 2220)
- `_REQUEST_OPLOCK_INPUT_BUFFER` (line 2236)
- `_REQUEST_OPLOCK_OUTPUT_BUFFER` (line 2263)
- `_SD_CHANGE_MACHINE_SID_INPUT` (line 2284)
- `_SD_CHANGE_MACHINE_SID_OUTPUT` (line 2294)
- `_SD_GLOBAL_CHANGE_INPUT` (line 2349)
- `_SD_GLOBAL_CHANGE_OUTPUT` (line 2371)
- `_EXTENDED_ENCRYPTED_DATA_INFO` (line 2405)
- `_LOOKUP_STREAM_FROM_CLUSTER_INPUT` (line 2415)
- `_LOOKUP_STREAM_FROM_CLUSTER_OUTPUT` (line 2421)
- `_LOOKUP_STREAM_FROM_CLUSTER_ENTRY` (line 2437)
- `_FILE_TYPE_NOTIFICATION_INPUT` (line 2445)
- `_SYSDBG_VIRTUAL` (line 2508)
- `_SYSDBG_PHYSICAL` (line 2515)
- `_SYSDBG_CONTROL_SPACE` (line 2522)
- `_SYSDBG_IO_SPACE` (line 2535)
- `_SYSDBG_MSR` (line 2545)
- `_SYSDBG_BUS_DATA` (line 2569)
- `_SYSDBG_TRIAGE_DUMP` (line 2579)
- `_IO_STATUS_BLOCK` (line 3178)
- `_X86_FLOATING_SAVE_AREA` (line 3192)
- `_X86_CONTEXT` (line 3205)
- `_PORT_VIEW` (line 3279)
- `_REMOTE_PORT_VIEW` (line 3288)
- `_MEMORY_WORKING_SET_BLOCK` (line 3312) - *added 21/03/2011*
- `_MEMORY_WORKING_SET_INFORMATION` (line 3325)
- `_MEMORY_WORKING_SET_EX_BLOCK` (line 3331)
- `_MEMORY_REGION_INFORMATION` (line 3348)
- `_MEMORY_WORKING_SET_EX_INFORMATION` (line 3356)
- `_ATOM_BASIC_INFORMATION` (line 3386)
- `_ATOM_TABLE_INFORMATION` (line 3394)
- `_SEMAPHORE_BASIC_INFORMATION` (line 3409)
- `_MUTANT_BASIC_INFORMATION` (line 3423)
- `_TIMER_BASIC_INFORMATION` (line 3438)
- `_OBJECT_BASIC_INFORMATION` (line 3473)
- `_OBJECT_NAME_INFORMATION` (line 3487)
- `_OBJECT_TYPE_INFORMATION` (line 3491)
- `_OBJECT_TYPES_INFORMATION` (line 3516)
- `_OBJECT_HANDLE_FLAG_INFORMATION` (line 3522)
- `_PLUGPLAY_EVENT_BLOCK` (line 3558)
- `_TIME_FIELDS` (line 3626)
- `_RTL_TIME_ZONE_INFORMATION` (line 3638)
- `_RTL_BITMAP_RUN` (line 3648)
- `_PARSE_MESSAGE_CONTEXT` (line 3654)
- `_RTL_RXACT_LOG` (line 3670)
- `_RTL_RXACT_CONTEXT` (line 3679)
- `_CPTABLEINFO` (line 3688)
- `_NLSTABLEINFO` (line 3703)
- `_RTL_RANGE` (line 3713)
- `_KEY_BASIC_INFORMATION` (line 3779)
- `_KEY_VALUE_BASIC_INFORMATION` (line 3799)
- `_KEY_VALUE_FULL_INFORMATION` (line 3806)
- `_KEY_VALUE_PARTIAL_INFORMATION` (line 3816)
- `_KEY_VALUE_PARTIAL_INFORMATION_ALIGN64` (line 3823)
- `_KEY_VALUE_ENTRY` (line 3829)
- `_CLIENT_ID` (line 3920)
- `_CLIENT_ID32` (line 3926)
- `_CLIENT_ID64` (line 3932)
- `_KSYSTEM_TIME` (line 3940)
- `_FILE_BASIC_INFORMATION` (line 3954)
- `_FILE_STANDARD_INFORMATION` (line 3962)
- `_FILE_INTERNAL_INFORMATION` (line 3971)
- `_FILE_EA_INFORMATION` (line 3975)
- `_FILE_ACCESS_INFORMATION` (line 3979)
- `_FILE_POSITION_INFORMATION` (line 3983)
- `_FILE_MODE_INFORMATION` (line 3987) - *ntddk wdm nthal*
- `_FILE_ALIGNMENT_INFORMATION` (line 3991)
- `_FILE_NAME_INFORMATION` (line 3995) - *ntddk nthal*
- `_FILE_ALL_INFORMATION` (line 4000)
- `_FILE_NETWORK_OPEN_INFORMATION` (line 4012)
- `_FILE_ATTRIBUTE_TAG_INFORMATION` (line 4022) - *ntddk wdm nthal*
- `_FILE_ALLOCATION_INFORMATION` (line 4027) - *ntddk nthal*
- `_FILE_COMPRESSION_INFORMATION` (line 4031)
- `_FILE_DISPOSITION_INFORMATION` (line 4040)
- `_FILE_END_OF_FILE_INFORMATION` (line 4044) - *ntddk nthal*
- `_FILE_VALID_DATA_LENGTH_INFORMATION` (line 4048) - *ntddk nthal*
- `_FILE_LINK_INFORMATION` (line 4052)
- `_FILE_MOVE_CLUSTER_INFORMATION` (line 4059)
- `_FILE_RENAME_INFORMATION` (line 4066)
- `_FILE_STREAM_INFORMATION` (line 4073)
- `_FILE_TRACKING_INFORMATION` (line 4081)
- `_FILE_COMPLETION_INFORMATION` (line 4087)
- `_FILE_PIPE_INFORMATION` (line 4092)
- `_FILE_PIPE_LOCAL_INFORMATION` (line 4097)
- `_FILE_PIPE_REMOTE_INFORMATION` (line 4110)
- `_FILE_MAILSLOT_QUERY_INFORMATION` (line 4115)
- `_FILE_MAILSLOT_SET_INFORMATION` (line 4123)
- `_FILE_REPARSE_POINT_INFORMATION` (line 4127)
- `_FILE_FULL_EA_INFORMATION` (line 4140)
- `_FILE_GET_EA_INFORMATION` (line 4150)
- `_FILE_GET_QUOTA_INFORMATION` (line 4160)
- `_FILE_QUOTA_INFORMATION` (line 4166)
- `_FILE_DIRECTORY_INFORMATION` (line 4188)
- `_FILE_FULL_DIR_INFORMATION` (line 4202)
- `_FILE_ID_FULL_DIR_INFORMATION` (line 4217)
- `_FILE_BOTH_DIR_INFORMATION` (line 4233)
- `_FILE_ID_BOTH_DIR_INFORMATION` (line 4250)
- `_FILE_NAMES_INFORMATION` (line 4268)
- `_FILE_OBJECTID_INFORMATION` (line 4275)
- `_SYSTEM_GDI_DRIVER_INFORMATION` (line 4293)
- `_SYSTEM_EXCEPTION_INFORMATION` (line 4303)
- `_SYSTEM_THREAD_INFORMATION` (line 4369) - *FIXED 21.02.2011 size for x64/x86*
- `_SYSTEM_EXTENDED_THREAD_INFORMATION` (line 4383)
- `_SYSTEM_POOL_ENTRY` (line 4394)
- `_SYSTEM_POOL_INFORMATION` (line 4406)
- `_SYSTEM_POOLTAG` (line 4416)
- `_SYSTEM_BIGPOOL_ENTRY` (line 4429)
- `_SYSTEM_POOLTAG_INFORMATION` (line 4441)
- `_SYSTEM_SESSION_POOLTAG_INFORMATION` (line 4447)
- `_SYSTEM_BIGPOOL_INFORMATION` (line 4454)
- `_SYSTEM_HANDLE_TABLE_ENTRY_INFO` (line 4459)
- `_SYSTEM_HANDLE_INFORMATION` (line 4470)
- `_SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX` (line 4476)
- `_SYSTEM_HANDLE_INFORMATION_EX` (line 4488)
- `_SYSTEM_SPECIAL_POOL_INFORMATION` (line 4495)
- `_SYSTEM_OBJECTTYPE_INFORMATION` (line 4501)
- `_SYSTEM_HIBERFILE_INFORMATION` (line 4516)
- `_SYSTEM_KERNEL_DEBUGGER_INFORMATION` (line 4522)
- `_SYSTEM_REGISTRY_QUOTA_INFORMATION` (line 4527)
- `_SYSTEM_CONTEXT_SWITCH_INFORMATION` (line 4533)
- `_SYSTEM_SESSION_MAPPED_VIEW_INFORMATION` (line 4548)
- `_SYSTEM_INTERRUPT_INFORMATION` (line 4556)
- `_SYSTEM_DPC_BEHAVIOR_INFORMATION` (line 4565)
- `_SYSTEM_LOOKASIDE_INFORMATION` (line 4573)
- `_SYSTEM_LEGACY_DRIVER_INFORMATION` (line 4585)
- `_SYSTEM_VDM_INSTEMUL_INFO` (line 4590)
- `_SYSTEM_TIMEOFDAY_INFORMATION` (line 4628)
- `_SYSTEM_BASIC_INFORMATION` (line 4645)
- `_SYSTEM_PROCESSOR_INFORMATION` (line 4659)
- `_SYSTEM_PROCESSOR_PERFORMANCE_INFORMATION` (line 4667)
- `_SYSTEM_PROCESSOR_IDLE_INFORMATION` (line 4676)
- `_SYSTEM_NUMA_INFORMATION` (line 4687)
- `_CACHE_DESCRIPTOR` (line 4716)
- `_SYSTEM_LOGICAL_PROCESSOR_INFORMATION` (line 4725)
- `_MEMORY_BASIC_INFORMATION` (line 4796)
- `_SYSTEM_PROCESSOR_POWER_INFORMATION` (line 4809)
- `_SYSTEM_QUERY_TIME_ADJUST_INFORMATION` (line 4831)
- `_SYSTEM_SET_TIME_ADJUST_INFORMATION` (line 4837)
- `_SYSTEM_PERFORMANCE_INFORMATION` (line 4842)
- `_SYSTEM_PROCESS_INFORMATION` (line 4919)
- `_SYSTEM_SESSION_PROCESS_INFORMATION` (line 4955)
- `_SYSTEM_MEMORY_INFO` (line 4961)
- `_SYSTEM_MEMORY_INFORMATION` (line 4969)
- `_SYSTEM_CALL_COUNT_INFORMATION` (line 4975)
- `_SYSTEM_DEVICE_INFORMATION` (line 4980)
- `_SYSTEM_FLAGS_INFORMATION` (line 4989)
- `_SYSTEM_CALL_TIME_INFORMATION` (line 4993)
- `_SYSTEM_OBJECT_INFORMATION` (line 4999)
- `_SYSTEM_PAGEFILE_INFORMATION` (line 5014)
- `_SYSTEM_VERIFIER_INFORMATION` (line 5022)
- `_SYSTEM_VERIFIER_INFORMATION_EX` (line 5057)
- `_SYSTEM_FILECACHE_INFORMATION` (line 5070)
- `_HOTPATCH_HOOK_DESCRIPTOR` (line 5094)
- `_SYSTEM_HOTPATCH_CODE_INFORMATION` (line 5105)
- `_KERNEL_USER_TIMES` (line 5154)
- `_SYSTEM_WATCHDOG_HANDLER_INFORMATION` (line 5194)
- `_SYSTEM_WATCHDOG_TIMER_INFORMATION` (line 5204)
- `_GDI_HANDLE_ENTRY` (line 5298)
- `_GDI_SHARED_MEMORY` (line 5321)
- `_CURDIR` (line 5333)
- `_RTL_DRIVE_LETTER_CURDIR` (line 5342)
- `_RTL_USER_PROCESS_PARAMETERS` (line 5353)
- `LIST_ENTRY32` (line 5422) - *if (_MSC_VER < 1300) && !defined(_WINDOWS_)*
- `LIST_ENTRY64` (line 5428)
- `_PEB_LDR_DATA32` (line 5437)
- `_LDR_DATA_TABLE_ENTRY32` (line 5452)
- `_CURDIR32` (line 5489)
- `_RTL_DRIVE_LETTER_CURDIR32` (line 5495)
- `_RTL_USER_PROCESS_PARAMETERS32` (line 5503)
- `_PEB32` (line 5543)
- `_GDI_TEB_BATCH32` (line 5644)
- `_NT_TIB32` (line 5655) - *if (_MSC_VER < 1300) && !defined(_WINDOWS_)  32 and 64 bit specific version for wow64 and the debugger*
- `_NT_TIB64` (line 5668)
- `_TEB32` (line 5682)
- `_TIB` (line 5738)
- `_NLS_USER_INFO` (line 5760)
- `_INIFILE_MAPPING_TARGET` (line 5802)
- `_INIFILE_MAPPING_VARNAME` (line 5808)
- `_INIFILE_MAPPING_APPNAME` (line 5816)
- `_INIFILE_MAPPING_FILENAME` (line 5824)
- `_INIFILE_MAPPING` (line 5832)
- `_PORT_MESSAGE` (line 5844)
- `_PORT_DATA_ENTRY` (line 5882)
- `_PORT_DATA_INFORMATION` (line 5887)
- `_CSR_API_CONNECTINFO` (line 5906)
- `_CSR_CLIENTCONNECT_MSG` (line 5922)
- `_CSR_CAPTURE_HEADER` (line 5934)
- `_CSR_NT_SESSION` (line 5965)
- `_CSR_API_MSG` (line 5973)
- `_CSR_CALLBACK_INFO` (line 5999)
- `_RTL_DYNAMIC_TIME_ZONE_INFORMATION` (line 6013)
- `_BASESRV_API_CONNECTINFO` (line 6023)
- `_BASE_NLS_SET_USER_INFO_MSG` (line 6068)
- `_BASE_NLS_GET_USER_INFO_MSG` (line 6075)
- `_BASE_NLS_UPDATE_CACHE_COUNT_MSG` (line 6081)
- `_BASE_UPDATE_VDM_ENTRY_MSG` (line 6086)
- `_BASE_GET_NEXT_VDM_COMMAND_MSG` (line 6097)
- `_BASE_SHUTDOWNPARAM_MSG` (line 6130)
- `_BASE_GETTEMPFILE_MSG` (line 6136)
- `_BASE_DEBUGPROCESS_MSG` (line 6141)
- `_BASE_CHECKVDM_MSG` (line 6148)
- `_BASE_GET_VDM_EXIT_CODE_MSG` (line 6181)
- `_BASE_DEFERREDCREATEPROCESS_MSG` (line 6188)
- `_BASE_EXITPROCESS_MSG` (line 6194)
- `_BASE_GET_SET_VDM_CUR_DIRS_MSG` (line 6198)
- `_BASE_SET_REENTER_COUNT` (line 6205)
- `_ACTIVATION_CONTEXT_RUN_LEVEL_INFORMATION` (line 6221)
- `_BASE_SXS_CREATEPROCESS_MSG` (line 6232)
- `_BASE_CREATEPROCESS_MSG` (line 6245)
- `_BASE_CREATETHREAD_MSG` (line 6261)
- `_BASE_MSG_SXS_HANDLES` (line 6268)
- `_BASE_EXIT_VDM_MSG` (line 6277)
- `_BASE_IS_FIRST_VDM_MSG` (line 6285)
- `_BASE_SET_REENTER_COUNT_MSG` (line 6291)
- `_BASE_BAT_NOTIFICATION_MSG` (line 6298)
- `_BASE_REGISTER_WOWEXEC_MSG` (line 6305)
- `_BASE_REFRESHINIFILEMAPPING_MSG` (line 6312)
- `_BASE_SET_TERMSRVCLIENTTIMEZONE` (line 6318)
- `_BASE_SET_TERMSRVAPPINSTALLMODE` (line 6326)
- `_BASE_SOUNDSENTRY_NOTIFICATION_MSG` (line 6332)
- `_BASE_DEFINEDOSDEVICE_MSG` (line 6338)
- `_BASE_MSG_SXS_STREAM` (line 6345)
- `_BASE_SXS_CREATE_ACTIVATION_CONTEXT_MSG` (line 6358)
- `_BASE_API_MSG` (line 6376)
- `_BASE_STATIC_SERVER_DATA` (line 6414)
- `_GDI_TEB_BATCH` (line 6442)
- `_ASSEMBLY_STORAGE_MAP_ENTRY` (line 6473)
- `_ASSEMBLY_STORAGE_MAP` (line 6480)
- `_ACTIVATION_CONTEXT_DATA` (line 6487)
- `_ACTIVATION_CONTEXT` (line 6498)
- `_PEB_FREE_BLOCK` (line 6515)
- `_PEB_LDR_DATA` (line 6520)
- `_INITIAL_TEB` (line 6533)
- `_WOW64_PROCESS` (line 6547)
- `_LDR_DLL_LOADED_NOTIFICATION_DATA` (line 6598)
- `_LDR_DLL_UNLOADED_NOTIFICATION_DATA` (line 6607)
- `_RTL_PROCESS_MODULE_INFORMATION` (line 6628)
- `_RTL_PROCESS_MODULES` (line 6642)
- `_RTL_PROCESS_MODULE_INFORMATION_EX` (line 6648)
- `_LDR_DATA_TABLE_ENTRY` (line 6671)
- `_FLS_CALLBACK_INFO` (line 6712)
- `_RTL_RELATIVE_NAME` (line 6726)
- `_RTL_RELATIVE_NAME_U` (line 6734)
- `_PEB` (line 6757) - *18/04/2011 updated*
- `_RTL_ACTIVATION_CONTEXT_STACK_FRAME` (line 6895)
- `_ACTIVATION_CONTEXT_STACK` (line 6903)
- `_TEB_ACTIVE_FRAME_CONTEXT` (line 6916)
- `_TEB_ACTIVE_FRAME_CONTEXT_EX` (line 6924)
- `_TEB_ACTIVE_FRAME` (line 6935) - *17/3/2011 updated*
- `_TEB_ACTIVE_FRAME_EX` (line 6944)
- `_TEB` (line 6953) - *18/04/2011*
- `_THREAD_BASIC_INFORMATION` (line 7112) - *added 18.04.2011*
- `_PROCESS_DEVICEMAP_INFORMATION` (line 7128) - *added 20.12.11 Process Device Map information NtQueryInformationProcess using ProcessDeviceMap NtSetInformationProcess using ProcessDeviceMap  #pra...*
- `_PROCESS_DEVICEMAP_INFORMATION_EX` (line 7140)
- `_PROCESS_BASIC_INFORMATION` (line 7154)
- `_PROCESS_EXTENDED_BASIC_INFORMATION` (line 7165)
- `_RTL_HEAP_ENTRY` (line 7183)
- `_RTL_HEAP_TAG` (line 7213)
- `_RTL_HEAP_INFORMATION` (line 7223)
- `_RTL_PROCESS_HEAPS` (line 7240)
- `_RTL_PROCESS_LOCK_INFORMATION` (line 7246)
- `_CONTEXT` (line 7279)
- `_EXCEPTION_RECORD` (line 7280)
- `_EXCEPTION_REGISTRATION_RECORD` (line 7293)
- `_CONTEXT` (line 7363)
- `_EXCEPTION_RECORD` (line 7450)
- `_EXCEPTION_RECORD32` (line 7466)
- `_EXCEPTION_RECORD64` (line 7475)
- `_EXCEPTION_POINTERS` (line 7489)
- `_RTL_QUERY_REGISTRY_TABLE` (line 7506)
- `_PROCESS_PRIORITY_CLASS` (line 7543)
- `_PROCESS_FOREGROUND_BACKGROUND` (line 7548)
- `_FILE_PATH` (line 7552)
- `_WINDOWS_OS_OPTIONS` (line 7569)
- `_BOOT_ENTRY` (line 7582)
- `_BOOT_OPTIONS` (line 7595)
- `_USER_SID` (line 7609)
- `_USER_PERMISSION` (line 7617)
- `_LSA_UNICODE_STRING` (line 8513)
- `_LSA_STRING` (line 8522)
- `_LSA_OBJECT_ATTRIBUTES` (line 8528)
- `_LSA_TRUST_INFORMATION` (line 8539)
- `_LSA_REFERENCED_DOMAIN_LIST` (line 8544)
- `_LSA_TRANSLATED_SID2` (line 8550) - *if (_WIN32_WINNT >= 0x0501)*
- `_LSA_TRANSLATED_NAME` (line 8558)
- `_POLICY_ACCOUNT_DOMAIN_INFO` (line 8564)
- `_POLICY_DNS_DOMAIN_INFO` (line 8569)
- `_SE_ADT_OBJECT_TYPE` (line 8715)
- `_SE_ADT_PARAMETER_ARRAY_ENTRY` (line 8723)
- `_SE_ADT_ACCESS_REASON` (line 8732)
- `_SE_ADT_PARAMETER_ARRAY` (line 8743)
- `_LSA_TRANSLATED_SID` (line 8914)
- `_POLICY_AUDIT_LOG_INFO` (line 8961)
- `_POLICY_AUDIT_EVENTS_INFO` (line 8972)
- `_POLICY_AUDIT_SUBCATEGORIES_INFO` (line 8980)
- `_POLICY_AUDIT_CATEGORIES_INFO` (line 8987)
- `_POLICY_PRIMARY_DOMAIN_INFO` (line 9012)
- `_POLICY_PD_ACCOUNT_INFO` (line 9019)
- `_POLICY_LSA_SERVER_ROLE_INFO` (line 9025)
- `_POLICY_REPLICA_SOURCE_INFO` (line 9031)
- `_POLICY_DEFAULT_QUOTA_INFO` (line 9038)
- `_POLICY_MODIFICATION_INFO` (line 9045)
- `_POLICY_AUDIT_FULL_SET_INFO` (line 9053)
- `_POLICY_AUDIT_FULL_QUERY_INFO` (line 9060)
- `_POLICY_DOMAIN_QUALITY_OF_SERVICE_INFO` (line 9095) - *if (_WIN32_WINNT == 0x0500)*
- `_POLICY_DOMAIN_EFS_INFO` (line 9103)
- `_POLICY_DOMAIN_KERBEROS_TICKET_INFO` (line 9112)
- `_TRUSTED_DOMAIN_NAME_INFO` (line 9155)
- `_TRUSTED_CONTROLLERS_INFO` (line 9161)
- `_TRUSTED_POSIX_OFFSET_INFO` (line 9168)
- `_TRUSTED_PASSWORD_INFO` (line 9174)
- `_TRUSTED_DOMAIN_INFORMATION_EX` (line 9237)
- `_TRUSTED_DOMAIN_INFORMATION_EX2` (line 9248)
- `_LSA_AUTH_INFORMATION` (line 9269)
- `_TRUSTED_DOMAIN_AUTH_INFORMATION` (line 9277)
- `_TRUSTED_DOMAIN_FULL_INFORMATION` (line 9288)
- `_TRUSTED_DOMAIN_FULL_INFORMATION2` (line 9296)
- `_TRUSTED_DOMAIN_SUPPORTED_ENCRYPTION_TYPES` (line 9304)
- `_LSA_FOREST_TRUST_DOMAIN_INFO` (line 9346)
- `_LSA_FOREST_TRUST_BINARY_DATA` (line 9368)
- `_LSA_FOREST_TRUST_RECORD` (line 9380)
- `_LSA_FOREST_TRUST_INFORMATION` (line 9415)
- `_LSA_FOREST_TRUST_COLLISION_RECORD` (line 9435)
- `_LSA_FOREST_TRUST_COLLISION_INFORMATION` (line 9444)
- `_LSA_ENUMERATION_INFORMATION` (line 9465)
- `_LSA_LAST_INTER_LOGON_INFO` (line 9493)
- `_SECURITY_LOGON_SESSION_DATA` (line 9502) - *if (_WIN32_WINNT >= 0x0501)*
- `_EFI_DRIVER_ENTRY` (line 9854)
- `_EFI_DRIVER_ENTRY_LIST` (line 9864)
- `_RTL_STACK_CONTEXT_ENTRY` (line 9872)
- `_RTL_STACK_CONTEXT` (line 9877)
- `_RTL_HEAP_PARAMETERS` (line 9889)
- `_RTL_AVL_TABLE` (line 9921)
- `_RTL_SPLAY_LINKS` (line 9923)
- `_RTL_AVL_TABLE` (line 9945)
- `_RTL_BALANCED_LINKS` (line 10015)
- `_RTL_AVL_TABLE` (line 10024)
- `_RTL_GENERIC_TABLE` (line 10039)
- `_GENERATE_NAME_CONTEXT` (line 10052)
- `_PREFIX_TABLE_ENTRY` (line 10068)
- `_PREFIX_TABLE` (line 10077)
- `_UNICODE_PREFIX_TABLE_ENTRY` (line 10084)
- `_UNICODE_PREFIX_TABLE` (line 10094)
- `_COMPRESSED_DATA_INFO` (line 10110)
- `_SECTION_IMAGE_INFORMATION` (line 10124)
- `_SECTION_IMAGE_INFORMATION64` (line 10161)
- `_RTL_BITMAP` (line 10185)
- `_RTL_RANGE_LIST` (line 10198)
- `_RANGE_LIST_ITERATOR` (line 10215)
- `_STARTUP_ARGUMENT` (line 10222)
- `_RTL_USER_PROCESS_INFORMATION` (line 10250)
- `_RTL_USER_PROCESS_INFORMATION64` (line 10258)
- `_RTL_RESOURCE` (line 10271)
- `_RTL_TRACE_BLOCK` (line 10290)
- `_RTL_TRACE_ENUMERATE` (line 10306)
- `_KLDR_DATA_TABLE_ENTRY` (line 10312)
- `_DISPATCHER_HEADER` (line 10347)
- `_KEVENT` (line 10380)
- `_KGATE` (line 10385)
- `_KSEMAPHORE` (line 10390)
- `_OWNER_ENTRY` (line 10396)
- `_ERESOURCE` (line 10403)
- `_HEAP_LOCK` (line 10441)
- `_HEAP_TUNING_PARAMETERS` (line 10450)
- `_HEAP_PSEUDO_TAG_ENTRY` (line 10456)
- `_HEAP_TAG_ENTRY` (line 10463)
- `_HEAP_ENTRY` (line 10473)
- `_HEAP_COUNTERS` (line 10496)
- `_HEAP` (line 10518)
- `_HEAP_FREE_ENTRY_EXTRA` (line 10575)
- `_HEAP_ENTRY_EXTRA` (line 10581)
- `_HEAP_VIRTUAL_ALLOC_ENTRY` (line 10589)
- `_XSTATE_FEATURE` (line 10674) - *Extended processor state configuration  if defined(_WINNT_) && defined(_MSC_VER) && _MSC_VER < 1300*
- `_XSTATE_CONFIGURATION` (line 10679)
- `_KUSER_SHARED_DATA` (line 10702)
- `_RTL_PROCESS_REFLECTION_INFORMATION` (line 10915) - *added 20/03/2011*
- `_VM_COUNTERS` (line 10923) - *FIXED 21.02.2011 size for x64*
- `_IO_COUNTERS` (line 10940) - *if (_MSC_VER < 1300) && !defined(_WINDOWS_)*
- `_SYSTEM_PROCESSES_INFORMATION` (line 10953) - *SystemProcessesAndThreadsInformation FIXED 21.02.2011 size for x64 (and as well for x86 too)*
- `_DBGKM_EXCEPTION` (line 10977)
- `_DBGKM_CREATE_THREAD` (line 10983)
- `_DBGKM_CREATE_PROCESS` (line 10989)
- `_DBGKM_EXIT_THREAD` (line 10999)
- `_DBGKM_EXIT_PROCESS` (line 11004)
- `_DBGKM_LOAD_DLL` (line 11009)
- `_DBGKM_UNLOAD_DLL` (line 11018)
- `_DBGUI_CREATE_THREAD` (line 11038)
- `_DBGUI_CREATE_PROCESS` (line 11044)
- `_DBGUI_WAIT_STATE_CHANGE` (line 11051)
- `_RTL_HEAP_TAG_INFO` (line 11086) - *added 21/03/2011 begin*
- `_RTL_HEAP_USAGE_ENTRY` (line 11101)
- `_RTL_HEAP_USAGE` (line 11110)
- `_RTL_HEAP_WALK_ENTRY` (line 11126)
- `_HEAP_DEBUGGING_INFORMATION` (line 11163)
- `_RTL_MEMORY_ZONE_SEGMENT` (line 11182)
- `_RTL_SRWLOCK` (line 11191) - *if defined(_WINNT_) && defined(_MSC_VER) && (_MSC_VER < 1300)*
- `_RTL_MEMORY_ZONE` (line 11196)
- `_RTL_PROCESS_VERIFIER_OPTIONS` (line 11204)
- `_VM_INFORMATION` (line 11218)
- `_MEMORY_RANGE_ENTRY` (line 11227)
- `_RTL_PROCESS_LOCKS` (line 11233)
- `_RTL_PROCESS_BACKTRACE_INFORMATION` (line 11240)
- `_RTL_PROCESS_BACKTRACES` (line 11248)
- `_RTL_DEBUG_INFORMATION` (line 11256)
- `_RTL_HANDLE_TABLE_ENTRY` (line 11330)
- `_RTL_HANDLE_TABLE` (line 11341)
- `_JOB_SET_ARRAY` (line 11353) - *if defined(_WINNT_) && (_MSC_VER < 1300) && !defined(_WINDOWS_)*
- `_EVENT_DATA_DESCRIPTOR` (line 11505)
- `_EVENT_DESCRIPTOR` (line 11512)
- `_EVENT_FILTER_DESCRIPTOR` (line 11528) - *EVENT_FILTER_DESCRIPTOR is used to pass in enable filter data item to a user callback function.*
- `_CHANNEL_MESSAGE` (line 11540) - *old nt4 channel stuff  #pragma pack(1) pragma pack()*
- `_HOTPATCH_HEADER` (line 11553)
- `_HOTPATCH_MODULE_DATA` (line 11572)
- `_HOTPATCH_MODULE_ENTRY` (line 11579)
- `_HOTPATCH_HOOK` (line 11585)
- `_RTL_PATCH_HEADER` (line 11594)
- `_RTL_UNLOAD_EVENT_TRACE` (line 21429)
- `_RTL_UNLOAD_EVENT_TRACE64` (line 21438)
- `_RTL_UNLOAD_EVENT_TRACE32` (line 21447)
- `addrinfo` (line 22497) - *BOOL WINAPI WriteConsoleA( IN  HANDLE  hConsoleOutput, IN  VOID    *lpBuffer, IN  DWORD   nNumberOfCharsToWrite, OUT LPDWORD lpNumberOfCharsWritten...*

#### `CoffeeLdr.h`
**Path:** `payloads/Demon/include/core/CoffeeLdr.h`

**Macros:**
- `DEMON_DOF_H` (line 6)
- `SIZE_OF_PAGE` (line 7)
- `PAGE_ALLIGN` (line 9)
- `IMAGE_SCN_MEM_NOT_CACHED` (line 10)
- `IMAGE_SCN_MEM_EXECUTE` (line 12)
- `IMAGE_SCN_MEM_READ` (line 13)
- `IMAGE_SCN_MEM_WRITE` (line 14)
- `SYMBOL_IS_A_FUNCTION` (line 17)
- `MACHINETYPE_AMD64` (line 42)
- `COFFEE_KEY_VALUE_MAX_KEY` (line 105)

**Structs:**
- `_COFFEE_PARAMS` (line 19)
- `_COFF_FILE_HEADER` (line 30)
- `_COFF_SECTION` (line 46)
- `_COFF_RELOC` (line 60)
- `_COFF_SYMBOL` (line 67)
- `_SECTION_MAP` (line 82)
- `_COFFEE` (line 88)
- `_COFFEE_KEY_VALUE` (line 108)

#### `Command.h`
**Path:** `payloads/Demon/include/core/Command.h`

**Macros:**
- `DEMON_COMMAND_H` (line 2)
- `DEMON_COMMAND_CHECKIN` (line 7)
- `DEMON_COMMAND_GET_JOB` (line 8)
- `DEMON_COMMAND_NO_JOB` (line 9)
- `DEMON_COMMAND_SLEEP` (line 10)
- `DEMON_COMMAND_PROC` (line 11)
- `DEMON_COMMAND_PROC_LIST` (line 12)
- `DEMON_COMMAND_FS` (line 13)
- `DEMON_COMMAND_INLINE_EXECUTE` (line 14)
- `DEMON_COMMAND_JOB` (line 15)
- `DEMON_COMMAND_INJECT_DLL` (line 16)
- `DEMON_COMMAND_INJECT_SHELLCODE` (line 17)
- `DEMON_COMMAND_SPAWN_DLL` (line 18)
- `DEMON_COMMAND_TOKEN` (line 19)
- `DEMON_COMMAND_ASSEMBLY_INLINE_EXECUTE` (line 20)
- `DEMON_COMMAND_ASSEMBLY_VERSIONS` (line 21)
- `DEMON_COMMAND_NET` (line 22)
- `DEMON_COMMAND_CONFIG` (line 23)
- `DEMON_COMMAND_SCREENSHOT` (line 24)
- `DEMON_COMMAND_PIVOT` (line 25)
- `DEMON_COMMAND_TRANSFER` (line 26)
- `DEMON_COMMAND_SOCKET` (line 27)
- `DEMON_COMMAND_KERBEROS` (line 28)
- `DEMON_COMMAND_MEM_FILE` (line 29)
- `DEMON_PACKAGE_DROPPED` (line 30)
- `DEMON_INFO` (line 31)
- `DEMON_OUTPUT` (line 33)
- `DEMON_ERROR` (line 34)
- `DEMON_EXIT` (line 35)
- `DEMON_KILL_DATE` (line 36)
- `BEACON_OUTPUT` (line 37)
- `DEMON_INITIALIZE` (line 38)
- `DEMON_COMMAND_INLINE_EXECUTE_EXCEPTION` (line 39)
- `DEMON_COMMAND_INLINE_EXECUTE_SYMBOL_NOT_FOUND` (line 41)
- `DEMON_COMMAND_INLINE_EXECUTE_RAN_OK` (line 42)
- `DEMON_COMMAND_INLINE_EXECUTE_COULD_NO_RUN` (line 43)
- `DOTNET_INFO_PATCHED` (line 44)
- `DOTNET_INFO_NET_VERSION` (line 46)
- `DOTNET_INFO_ENTRYPOINT_EXECUTED` (line 47)
- `DOTNET_INFO_FINISHED` (line 48)
- `DOTNET_INFO_FAILED` (line 49)
- `CALLBACK_ERROR_WIN32` (line 50)
- `CALLBACK_ERROR_COFFEXEC` (line 52)
- `CALLBACK_ERROR_TOKEN` (line 53)
- `DEMON_CONFIG_SHOW_ALL` (line 56)
- `DEMON_CONFIG_IMPLANT_SLEEPMASK` (line 57)
- `DEMON_CONFIG_IMPLANT_SPFTHREADADDR` (line 59)
- `DEMON_CONFIG_IMPLANT_VERBOSE` (line 60)
- `DEMON_CONFIG_IMPLANT_SLEEP_TECHNIQUE` (line 61)
- `DEMON_CONFIG_IMPLANT_COFFEE_THREADED` (line 62)
- `DEMON_CONFIG_IMPLANT_COFFEE_VEH` (line 63)
- `DEMON_CONFIG_MEMORY_ALLOC` (line 64)
- `DEMON_CONFIG_MEMORY_EXECUTE` (line 66)
- `DEMON_CONFIG_INJECTION_TECHNIQUE` (line 67)
- `DEMON_CONFIG_INJECTION_SPOOFADDR` (line 69)
- `DEMON_CONFIG_INJECTION_SPAWN64` (line 70)
- `DEMON_CONFIG_INJECTION_SPAWN32` (line 72)
- `DEMON_CONFIG_KILLDATE` (line 73)
- `DEMON_CONFIG_WORKINGHOURS` (line 74)
- `DEMON_NET_COMMAND_DOMAIN` (line 75)
- `DEMON_NET_COMMAND_LOGONS` (line 77)
- `DEMON_NET_COMMAND_SESSIONS` (line 78)
- `DEMON_NET_COMMAND_COMPUTER` (line 79)
- `DEMON_NET_COMMAND_DCLIST` (line 80)
- `DEMON_NET_COMMAND_SHARE` (line 81)
- `DEMON_NET_COMMAND_LOCALGROUP` (line 82)
- `DEMON_NET_COMMAND_GROUP` (line 83)
- `DEMON_NET_COMMAND_USER` (line 84)
- `DEMON_PIVOT_LIST` (line 85)
- `DEMON_PIVOT_SMB_CONNECT` (line 87)
- `DEMON_PIVOT_SMB_DISCONNECT` (line 89)
- `DEMON_PIVOT_SMB_COMMAND` (line 90)
- `DEMON_INFO_MEM_ALLOC` (line 91)
- `DEMON_INFO_MEM_EXEC` (line 93)
- `DEMON_INFO_MEM_PROTECT` (line 94)
- `DEMON_INFO_PROC_CREATE` (line 95)
- `DEMON_CHECKIN_OPTION_PIVOTS` (line 96)
- `DEMON_COMMAND_JOB_LIST` (line 98)
- `DEMON_COMMAND_JOB_SUSPEND` (line 100)
- `DEMON_COMMAND_JOB_RESUME` (line 101)
- `DEMON_COMMAND_JOB_KILL_REMOVE` (line 102)
- `DEMON_COMMAND_JOB_DIED` (line 103)
- `DEMON_COMMAND_TRANSFER_LIST` (line 104)
- `DEMON_COMMAND_TRANSFER_STOP` (line 106)
- `DEMON_COMMAND_TRANSFER_RESUME` (line 107)
- `DEMON_COMMAND_TRANSFER_REMOVE` (line 108)
- `DEMON_COMMAND_PROC_MODULES` (line 109)
- `DEMON_COMMAND_PROC_GREP` (line 111)
- `DEMON_COMMAND_PROC_CREATE` (line 112)
- `DEMON_COMMAND_PROC_MEMORY` (line 113)
- `DEMON_COMMAND_PROC_KILL` (line 114)
- `DEMON_COMMAND_TOKEN_IMPERSONATE` (line 115)
- `DEMON_COMMAND_TOKEN_STEAL` (line 117)
- `DEMON_COMMAND_TOKEN_LIST` (line 118)
- `DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST` (line 119)
- `DEMON_COMMAND_TOKEN_MAKE` (line 120)
- `DEMON_COMMAND_TOKEN_GET_UID` (line 121)
- `DEMON_COMMAND_TOKEN_REVERT` (line 122)
- `DEMON_COMMAND_TOKEN_REMOVE` (line 123)
- `DEMON_COMMAND_TOKEN_CLEAR` (line 124)
- `DEMON_COMMAND_TOKEN_FIND_TOKENS` (line 125)
- `DEMON_COMMAND_FS_DIR` (line 126)
- `DEMON_COMMAND_FS_DOWNLOAD` (line 128)
- `DEMON_COMMAND_FS_UPLOAD` (line 129)
- `DEMON_COMMAND_FS_CD` (line 130)
- `DEMON_COMMAND_FS_REMOVE` (line 131)
- `DEMON_COMMAND_FS_MKDIR` (line 132)
- `DEMON_COMMAND_FS_COPY` (line 133)
- `DEMON_COMMAND_FS_MOVE` (line 134)
- `DEMON_COMMAND_FS_GET_PWD` (line 135)
- `DEMON_COMMAND_FS_CAT` (line 136)

#### `Dotnet.h`
**Path:** `payloads/Demon/include/core/Dotnet.h`

*No symbols extracted*

#### `Download.h`
**Path:** `payloads/Demon/include/core/Download.h`

**Macros:**
- `DEMON_FILETRANFER_H` (line 2)
- `DOWNLOAD_MODE_OPEN` (line 5)
- `DOWNLOAD_MODE_WRITE` (line 7)
- `DOWNLOAD_MODE_CLOSE` (line 8)
- `DOWNLOAD_REASON_FINISHED` (line 9)
- `DOWNLOAD_REASON_REMOVED` (line 11)
- `DOWNLOAD_STATE_RUNNING` (line 12)
- `DOWNLOAD_STATE_STOPPED` (line 14)
- `DOWNLOAD_STATE_REMOVE` (line 15)

**Structs:**
- `_DOWNLOAD_DATA` (line 23)
- `_MEM_FILE` (line 48) - */* What we have left to read. LONGLONG Size; /* What we already read. LONGLONG ReadSize; /* Current state of file transfer DownloadState State; /* ...*

#### `HwBpEngine.h`
**Path:** `payloads/Demon/include/core/HwBpEngine.h`

**Macros:**
- `DEMON_HWBPENGINE_H` (line 2)

**Structs:**
- `_BP_LIST` (line 7)
- `_HWBP_ENGINE` (line 18)

#### `HwBpExceptions.h`
**Path:** `payloads/Demon/include/core/HwBpExceptions.h`

**Macros:**
- `DEMON_HWBPEXCEPTIONS_H` (line 2)
- `EXCEPTION_DUMP` (line 7)
- `EXCEPTION_SET_RIP` (line 28)
- `EXCEPTION_SET_RET` (line 30)
- `EXCEPTION_RESUME` (line 31)
- `EXCEPTION_GET_RET` (line 32)
- `EXCEPTION_ADJ_STACK` (line 33)
- `EXCEPTION_ARG_1` (line 34)
- `EXCEPTION_ARG_2` (line 35)
- `EXCEPTION_ARG_3` (line 36)
- `EXCEPTION_ARG_4` (line 37)
- `EXCEPTION_ARG_5` (line 38)
- `EXCEPTION_ARG_6` (line 39)
- `EXCEPTION_ARG_7` (line 40)
- `EXCEPTION_ARG_1` (line 43)
- `EXCEPTION_ARG_2` (line 45)
- `EXCEPTION_ARG_3` (line 46)
- `EXCEPTION_ARG_4` (line 47)
- `EXCEPTION_ARG_5` (line 48)
- `EXCEPTION_ARG_6` (line 49)
- `EXCEPTION_ARG_7` (line 50)

#### `Jobs.h`
**Path:** `payloads/Demon/include/core/Jobs.h`

**Macros:**
- `DEMON_JOBS_HPP` (line 2)
- `JOB_TYPE_THREAD` (line 5)
- `JOB_TYPE_PROCESS` (line 7)
- `JOB_TYPE_TRACK_PROCESS` (line 8)
- `JOB_STATE_RUNNING` (line 9)
- `JOB_STATE_SUSPENDED` (line 11)
- `JOB_STATE_DEAD` (line 12)

**Structs:**
- `_JOB_DATA` (line 14)

#### `Kerberos.h`
**Path:** `payloads/Demon/include/core/Kerberos.h`

**Macros:**
- `DEMON_KERBEROS_H` (line 3)
- `KERBEROS_COMMAND_LUID` (line 6)
- `KERBEROS_COMMAND_KLIST` (line 8)
- `KERBEROS_COMMAND_PURGE` (line 9)
- `KERBEROS_COMMAND_PTT` (line 10)
- `_KerbSubmitTicketMessage` (line 11)
- `KERB_USE_DEFAULT_TICKET_FLAGS` (line 13)
- `KERB_RETRIEVE_TICKET_DEFAULT` (line 15)
- `KERB_RETRIEVE_TICKET_DONT_USE_CACHE` (line 17)
- `KERB_RETRIEVE_TICKET_USE_CACHE_ONLY` (line 18)
- `KERB_RETRIEVE_TICKET_USE_CREDHANDLE` (line 19)
- `KERB_RETRIEVE_TICKET_AS_KERB_CRED` (line 20)
- `KERB_RETRIEVE_TICKET_WITH_SEC_CRED` (line 21)
- `KERB_RETRIEVE_TICKET_CACHE_TICKET` (line 22)
- `FIELD_LENGTH` (line 23)
- `__SECHANDLE_DEFINED__` (line 147)

**Structs:**
- `_TICKET_INFORMATION` (line 26)
- `_SESSION_INFORMATION` (line 40)
- `KERB_CRYPTO_KEY` (line 96)
- `KERB_CRYPTO_KEY32` (line 102)
- `_KERB_SUBMIT_TKT_REQUEST` (line 108)
- `_KERB_PURGE_TKT_CACHE_REQUEST` (line 117)
- `_KERB_TICKET_CACHE_INFO_EX` (line 124)
- `_KERB_QUERY_TKT_CACHE_EX_RESPONSE` (line 136)
- `_SecHandle` (line 143) - *ifndef __SECHANDLE_DEFINED__*
- `_KERB_RETRIEVE_TKT_REQUEST` (line 151)
- `_KERB_EXTERNAL_NAME` (line 161)
- `_KERB_EXTERNAL_TICKET` (line 167)
- `_KERB_RETRIEVE_TKT_RESPONSE` (line 186)
- `_KERB_QUERY_TKT_CACHE_REQUEST` (line 190)
- `_LOGON_SESSION_DATA` (line 195)

#### `Memory.h`
**Path:** `payloads/Demon/include/core/Memory.h`

**Macros:**
- `DEMON_MEMORY_H` (line 2)

#### `MiniStd.h`
**Path:** `payloads/Demon/include/core/MiniStd.h`

**Macros:**
- `DEMON_DSTDIO_H` (line 2)
- `MemCopy` (line 5)
- `MemSet` (line 7)
- `MemZero` (line 8)
- `NO_INLINE` (line 9)

#### `ObjectApi.h`
**Path:** `payloads/Demon/include/core/ObjectApi.h`

**Macros:**
- `DEMON_OBJECTAPI_H` (line 2)
- `CALLBACK_OUTPUT` (line 16)
- `CALLBACK_OUTPUT_OEM` (line 18)
- `CALLBACK_ERROR` (line 19)
- `CALLBACK_OUTPUT_UTF8` (line 20)
- `MASK_SIZE` (line 33)
- `DATA_STORE_TYPE_EMPTY` (line 45)
- `DATA_STORE_TYPE_GENERAL_FILE` (line 47)

#### `Package.h`
**Path:** `payloads/Demon/include/core/Package.h`

**Macros:**
- `CALLBACK_PACKAGE_H` (line 2)
- `DEMON_MAX_REQUEST_LENGTH` (line 5)
- `PACKAGE_ERROR_WIN32` (line 101)
- `PACKAGE_ERROR_NTSTATUS` (line 103)

**Structs:**
- `_PACKAGE` (line 8)

#### `Parser.h`
**Path:** `payloads/Demon/include/core/Parser.h`

**Macros:**
- `DEMON_PARSER_H` (line 2)

#### `Pivot.h`
**Path:** `payloads/Demon/include/core/Pivot.h`

**Macros:**
- `DEMON_PIVOT_H` (line 2)
- `MAX_SMB_PACKETS_PER_LOOP` (line 5)

**Structs:**
- `_PIVOT_DATA` (line 8)

#### `Process.h`
**Path:** `payloads/Demon/include/core/Process.h`

**Macros:**
- `DEMON_PROCESS_H` (line 2)

#### `Runtime.h`
**Path:** `payloads/Demon/include/core/Runtime.h`

**Macros:**
- `DEMON_RUNTIME_H` (line 2)

#### `SleepObf.h`
**Path:** `payloads/Demon/include/core/SleepObf.h`

**Macros:**
- `DEMON_SLEEPOBF_H` (line 3)
- `SLEEPOBF_NO_OBF` (line 6)
- `SLEEPOBF_EKKO` (line 8)
- `SLEEPOBF_ZILEAN` (line 9)
- `SLEEPOBF_FOLIAGE` (line 10)
- `SLEEPOBF_BYPASS_NONE` (line 11)
- `SLEEPOBF_BYPASS_JMPRAX` (line 13)
- `SLEEPOBF_BYPASS_JMPRBX` (line 14)
- `OBF_JMP` (line 15)

**Structs:**
- `_SLEEP_PARAM` (line 32)

#### `Socket.h`
**Path:** `payloads/Demon/include/core/Socket.h`

**Macros:**
- `SOCKET_TYPE_NONE` (line 2)
- `SOCKET_TYPE_REVERSE_PORTFWD` (line 4)
- `SOCKET_TYPE_REVERSE_PROXY` (line 5)
- `SOCKET_TYPE_CLIENT` (line 6)
- `SOCKET_COMMAND_RPORTFWD_ADD` (line 7)
- `SOCKET_COMMAND_RPORTFWD_ADDLCL` (line 9)
- `SOCKET_COMMAND_RPORTFWD_LIST` (line 10)
- `SOCKET_COMMAND_RPORTFWD_CLEAR` (line 11)
- `SOCKET_COMMAND_RPORTFWD_REMOVE` (line 12)
- `SOCKET_COMMAND_SOCKSPROXY_ADD` (line 13)
- `SOCKET_COMMAND_SOCKSPROXY_LIST` (line 15)
- `SOCKET_COMMAND_SOCKSPROXY_REMOVE` (line 16)
- `SOCKET_COMMAND_SOCKSPROXY_CLEAR` (line 17)
- `SOCKET_COMMAND_OPEN` (line 18)
- `SOCKET_COMMAND_READ` (line 20)
- `SOCKET_COMMAND_WRITE` (line 21)
- `SOCKET_COMMAND_CLOSE` (line 22)
- `SOCKET_COMMAND_CONNECT` (line 23)
- `SOCKET_ERROR_ALREADY_BOUND` (line 26)

**Structs:**
- `sockaddr_in6` (line 28)
- `_SOCKET_DATA` (line 39)

#### `Spoof.h`
**Path:** `payloads/Demon/include/core/Spoof.h`

**Macros:**
- `DEMON_SPOOF_H` (line 2)
- `SPOOF_X` (line 18)
- `SPOOF_A` (line 20)
- `SPOOF_B` (line 21)
- `SPOOF_C` (line 22)
- `SPOOF_D` (line 23)
- `SPOOF_E` (line 24)
- `SPOOF_F` (line 25)
- `SPOOF_G` (line 26)
- `SPOOF_H` (line 27)
- `SETUP_ARGS` (line 28)
- `SPOOF_MACRO_CHOOSER` (line 29)
- `SpoofFunc` (line 30)

#### `SysNative.h`
**Path:** `payloads/Demon/include/core/SysNative.h`

**Macros:**
- `DEMON_SYSNATIVE_H` (line 2)
- `OPT` (line 9)
- `SYSCALL_INVOKE` (line 11)

#### `Syscalls.h`
**Path:** `payloads/Demon/include/core/Syscalls.h`

**Macros:**
- `DEMON_SYSCALLS_H` (line 3)
- `SYS_ASM_RET` (line 9)
- `SYS_RANGE` (line 10)
- `SYSCALL_ASM` (line 12)
- `SSN_OFFSET_1` (line 13)
- `SSN_OFFSET_2` (line 14)
- `SYSCALL_ASM` (line 16)
- `SSN_OFFSET_1` (line 17)
- `SSN_OFFSET_2` (line 18)
- `SYS_EXTRACT` (line 20)

**Structs:**
- `_SYS_CONFIG` (line 32)

#### `Thread.h`
**Path:** `payloads/Demon/include/core/Thread.h`

**Macros:**
- `DEMON_THREAD_H` (line 2)
- `THREAD_METHOD_DEFAULT` (line 8)
- `THREAD_METHOD_CREATEREMOTETHREAD` (line 9)
- `THREAD_METHOD_NTCREATEHREADEX` (line 10)
- `THREAD_METHOD_NTQUEUEAPCTHREAD` (line 11)

**Structs:**
- `_WOW64CONTEXT` (line 25) - *The context used for injection via migrate_via_remotethread_wow64*

#### `Token.h`
**Path:** `payloads/Demon/include/core/Token.h`

**Macros:**
- `DEMON_TOKEN_H` (line 2)
- `TOKEN_TYPE_STOLEN` (line 6)
- `TOKEN_TYPE_MAKE_NETWORK` (line 8)
- `TOKEN_OWNER_FLAG_DEFAULT` (line 9)
- `TOKEN_OWNER_FLAG_USER` (line 11)
- `TOKEN_OWNER_FLAG_DOMAIN` (line 12)
- `MAX_PROCESSES` (line 13)
- `BUF_SIZE` (line 15)
- `MAX_USERNAME` (line 16)
- `RtlOffsetToPointer` (line 17)
- `ALIGN_UP_TYPE` (line 21)
- `ALIGN_UP` (line 25)
- `ObjectTypesInformation` (line 27)
- `OBJECT_TYPES_FIRST_ENTRY` (line 29)
- `OBJECT_TYPES_NEXT_ENTRY` (line 32)

**Structs:**
- `_PROCESS_LIST` (line 37)
- `_USER_TOKEN_DATA` (line 43)
- `_OBJECT_TYPE_INFORMATION_V2` (line 53)
- `_TOKEN_LIST_DATA` (line 80) - *ULONG HighWaterHandleTableUsage; ULONG InvalidAttributes; GENERIC_MAPPING GenericMapping; ULONG ValidAccessMask; BOOLEAN SecurityRequired; BOOLEAN ...*

#### `Transport.h`
**Path:** `payloads/Demon/include/core/Transport.h`

**Macros:**
- `DEMON_INTERNET_H` (line 2)
- `PIPE_BUFFER_MAX` (line 7)

#### `TransportHttp.h`
**Path:** `payloads/Demon/include/core/TransportHttp.h`

**Macros:**
- `DEMON_TRANSPORTHTTP_H` (line 2)
- `TRANSPORT_HTTP_ROTATION_ROUND_ROBIN` (line 10)
- `TRANSPORT_HTTP_ROTATION_RANDOM` (line 12)
- `ERROR_INTERNET_CANNOT_CONNECT` (line 13)

**Structs:**
- `_HOST_DATA` (line 15)

#### `TransportSmb.h`
**Path:** `payloads/Demon/include/core/TransportSmb.h`

**Macros:**
- `DEMON_TRANSPORTSMB_H` (line 2)

#### `Win32.h`
**Path:** `payloads/Demon/include/core/Win32.h`

**Functions:**
- `__attribute__` (line 100) `typedef struct __attribute__((packed))`

**Macros:**
- `DEMON_WIN32_H` (line 2)
- `HASH_KEY` (line 17)
- `WIN_FUNC` (line 19)
- `DEREF` (line 20)
- `DEREF_32` (line 22)
- `DEREF_16` (line 23)
- `MAX` (line 24)
- `MIN` (line 26)

**Structs:**
- `_DIR_OR_FILE` (line 28)
- `_SUB_DIR` (line 39)
- `_ROOT_DIR` (line 46)
- `_BUFFER` (line 64)
- `_ANONPIPE` (line 70)
- `_PROC_THREAD_ATTRIBUTE_ENTRY` (line 93)
- `_PROC_THREAD_ATTRIBUTE_LIST` (line 107)

#### `AesCrypt.h`
**Path:** `payloads/Demon/include/crypt/AesCrypt.h`

**Macros:**
- `_AES_H_` (line 2)
- `CTR` (line 5)
- `AES256` (line 7)
- `CTR` (line 10)
- `AES_BLOCKLEN` (line 12)
- `AES_KEYLEN` (line 14)
- `AES_keyExpSize` (line 15)

#### `Inject.h`
**Path:** `payloads/Demon/include/inject/Inject.h`

**Macros:**
- `DEMON_BASEINJECT_H` (line 3)
- `INJECTION_TECHNIQUE_WIN32` (line 9)
- `INJECTION_TECHNIQUE_SYSCALL` (line 11)
- `INJECTION_TECHNIQUE_APC` (line 12)
- `SPAWN_TECHNIQUE_SYSCALL` (line 13)
- `SPAWN_TECHNIQUE_APC` (line 15)
- `SPAWN_TECHNIQUE_DEFAULT` (line 18)
- `INJECTION_TECHNIQUE_DEFAULT` (line 19)
- `INJECT_ERROR_SUCCESS` (line 48)
- `INJECT_ERROR_FAILED` (line 49)
- `INJECT_ERROR_INVALID_PARAM` (line 50)
- `INJECT_ERROR_PROCESS_ARCH_MISMATCH` (line 51)
- `INJECT_WAY_SPAWN` (line 52)
- `INJECT_WAY_INJECT` (line 54)
- `INJECT_WAY_EXECUTE` (line 55)

**Structs:**
- `INJECTION_CTX` (line 31)

#### `InjectUtil.h`
**Path:** `payloads/Demon/include/inject/InjectUtil.h`

**Macros:**
- `DEMON_INJECTUTIL_H` (line 2)
- `DEREF_32` (line 6)
- `DEREF_16` (line 8)
- `PROC_THREAD_ATTRIBUTE_NUMBER` (line 11)
- `PROC_THREAD_ATTRIBUTE_THREAD` (line 13)
- `PROC_THREAD_ATTRIBUTE_INPUT` (line 14)
- `PROC_THREAD_ATTRIBUTE_ADDITIVE` (line 15)
- `ProcThreadAttributeValue` (line 16)
- `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86` (line 24)
- `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64` (line 26)
- `ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS` (line 27)

#### `Core.h`
**Path:** `payloads/DllLdr/Include/Core.h`

**Macros:**
- `NTDLL_HASH` (line 4)
- `SYS_LDRLOADDLL` (line 6)
- `SYS_NTALLOCATEVIRTUALMEMORY` (line 8)
- `SYS_NTPROTECTEDVIRTUALMEMORY` (line 9)
- `SYS_NTFLUSHINSTRUCTIONCACHE` (line 10)
- `DLLEXPORT` (line 11)
- `NAKED` (line 13)
- `FORCE_INLINE` (line 14)
- `WIN32_FUNC` (line 15)
- `U_PTR` (line 16)
- `C_PTR` (line 18)
- `RVA2VA` (line 19)
- `DLL_QUERY_HMODULE` (line 20)
- `IMAGE_REL_TYPE` (line 24)
- `IMAGE_REL_TYPE` (line 26)

#### `Macro.h`
**Path:** `payloads/DllLdr/Include/Macro.h`

**Macros:**
- `HASH_KEY` (line 3)
- `PPEB_PTR` (line 7)
- `PPEB_PTR` (line 9)
- `SEC` (line 11)
- `U_PTR` (line 13)
- `C_PTR` (line 14)
- `NtCurrentProcess` (line 15)
- `GET_SYMBOL` (line 16)

#### `Native.h`
**Path:** `payloads/DllLdr/Include/Native.h`

**Macros:**
- `GDI_HANDLE_BUFFER_SIZE32` (line 14)
- `GDI_HANDLE_BUFFER_SIZE64` (line 16)
- `GDI_HANDLE_BUFFER_SIZE` (line 19)
- `GDI_HANDLE_BUFFER_SIZE` (line 21)

**Structs:**
- `_myUNICODE_STRING` (line 2)
- `_CURDIR` (line 9)
- `_PEB_LDR_DATA` (line 28)
- `_PEB` (line 41)
- `_LDR_DATA_TABLE_ENTRY` (line 173)

#### `Core.h`
**Path:** `payloads/Shellcode/Include/Core.h`

**Macros:**
- `PAGE_SIZE` (line 8)
- `MemCopy` (line 10)
- `NTDLL_HASH` (line 11)
- `SYS_LDRLOADDLL` (line 12)
- `SYS_NTALLOCATEVIRTUALMEMORY` (line 14)
- `SYS_NTPROTECTEDVIRTUALMEMORY` (line 15)

#### `Macro.h`
**Path:** `payloads/Shellcode/Include/Macro.h`

**Macros:**
- `PPEB_PTR` (line 5)
- `PPEB_PTR` (line 7)
- `SEC` (line 9)
- `U_PTR` (line 11)
- `C_PTR` (line 12)
- `NtCurrentProcess` (line 13)
- `GET_SYMBOL` (line 14)

#### `Utils.h`
**Path:** `payloads/Shellcode/Include/Utils.h`

*No symbols extracted*

#### `Win32.h`
**Path:** `payloads/Shellcode/Include/Win32.h`

*No symbols extracted*

### HPP (28 files)

#### `CmdLine.hpp`
**Path:** `client/include/Havoc/CmdLine.hpp`

**Classes:**
- `lexical_cast_t` (line 45)
- `parser` (line 308)
- `option_base` (line 621)
- `option_without_value` (line 638)
- `option_with_value` (line 694)

**Functions:**
- `cast` (line 46) `public:
            static Target cast(const Source &arg)`
- `cast` (line 59) `public:
            static Target cast(const Source &arg)`
- `cast` (line 67) `public:
            static std::string cast(const Source &arg)`
- `cast` (line 77) `public:
            static Target cast(const std::string &arg)`
- `lexical_cast` (line 98) `Target lexical_cast(const Source &arg)`
- `demangle` (line 102) `static inline std::string demangle(const std::string &name)`
- `readable_typename` (line 111) `template <class T>
        std::string readable_typename()`
- `default_value` (line 117) `template <class T>
        std::string default_value(T def)`
- `cmdline_error` (line 135) `public:
        cmdline_error(const std::string &msg): msg(msg)`
- `what` (line 138) `const char *what() const throw()`
- `operator` (line 145) `T operator()(const std::string &str)`
- `range_reader` (line 152) `range_reader(const T &low, const T &high): low(low), high(high)`
- `operator` (line 153) `T operator()(const std::string &s) const`
- `range` (line 161) `template <class T>
    range_reader<T> range(const T &low, const T &high)`
- `operator` (line 170) `T operator()(const std::string &s)`
- `add` (line 176) `void add(const T &v)`
- `oneof` (line 180) `template <class T>
    oneof_reader<T> oneof(T a1)`
- `oneof` (line 188) `template <class T>
    oneof_reader<T> oneof(T a1, T a2)`
- `oneof` (line 197) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3)`
- `oneof` (line 207) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4)`
- `oneof` (line 218) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)`
- `oneof` (line 230) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)`
- `oneof` (line 243) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)`
- `oneof` (line 257) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)`
- `oneof` (line 272) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)`
- `oneof` (line 288) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...`
- `parser` (line 309) `public:
        parser()`
- `add` (line 317) `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- `add` (line 325) `template <class T>
        void add(const std::string &name,
                 char short_name=0,
...`
- `add` (line 336) `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- `footer` (line 346) `void footer(const std::string &f)`
- `set_program_name` (line 350) `void set_program_name(const std::string &name)`
- `exist` (line 354) `bool exist(const std::string &name) const`
- `get` (line 359) `template <class T>
        const T &get(const std::string &name) const`
- `rest` (line 367) `const std::vector<std::string> &rest() const`
- `parse` (line 371) `bool parse(const std::string &arg)`
- `parse` (line 413) `bool parse(const std::vector<std::string> &args)`
- `parse` (line 423) `bool parse(int argc, const char * const argv[])`
- `parse_check` (line 524) `void parse_check(const std::string &arg)`
- `parse_check` (line 530) `void parse_check(const std::vector<std::string> &args)`
- `parse_check` (line 536) `void parse_check(int argc, char *argv[])`
- `error` (line 542) `std::string error() const`
- `error_full` (line 546) `std::string error_full() const`
- `usage` (line 553) `std::string usage() const`
- `check` (line 584) `private:

        void check(int argc, bool ok)`
- `set_option` (line 598) `void set_option(const std::string &name)`
- `set_option` (line 609) `void set_option(const std::string &name, const std::string &value)`
- `option_without_value` (line 639) `public:
            option_without_value(const std::string &name,
                               ...`
- `has_value` (line 646) `bool has_value() const`
- `set` (line 648) `bool set()`
- `set` (line 653) `bool set(const std::string &)`
- `has_set` (line 657) `bool has_set() const`
- `valid` (line 661) `bool valid() const`
- `must` (line 665) `bool must() const`
- `name` (line 669) `const std::string &name() const`
- `short_name` (line 673) `char short_name() const`
- `description` (line 677) `const std::string &description() const`
- `short_description` (line 681) `std::string short_description() const`
- `option_with_value` (line 695) `public:
            option_with_value(const std::string &name,
                              char...`
- `get` (line 706) `const T &get() const`
- `has_value` (line 710) `bool has_value() const`
- `set` (line 712) `bool set()`
- `set` (line 716) `bool set(const std::string &value)`
- `has_set` (line 727) `bool has_set() const`
- `valid` (line 731) `bool valid() const`
- `must` (line 736) `bool must() const`
- `name` (line 740) `const std::string &name() const`
- `short_name` (line 744) `char short_name() const`
- `description` (line 748) `const std::string &description() const`
- `short_description` (line 752) `std::string short_description() const`
- `full_description` (line 756) `protected:
            std::string full_description(const std::string &desc)`
- `option_with_value_with_reader` (line 779) `public:
            option_with_value_with_reader(const std::string &name,
                      ...`
- `read` (line 788) `private:
            T read(const std::string &s)`

**Structs:**
- `is_same` (line 88)
- `default_reader` (line 144)
- `range_reader` (line 151)
- `oneof_reader` (line 169)

#### `Connector.hpp`
**Path:** `client/include/Havoc/Connector.hpp`

**Classes:**
- `Connector` (line 14)

**Macros:**
- `HAVOC_CONNECTOR_HPP` (line 2)

#### `DBManager.hpp`
**Path:** `client/include/Havoc/DBManager/DBManager.hpp`

**Macros:**
- `HAVOC_DBMANAGER_HPP` (line 2)

#### `Havoc.hpp`
**Path:** `client/include/Havoc/Havoc.hpp`

**Macros:**
- `HAVOC_HAVOC_HPP` (line 2)

#### `Packager.hpp`
**Path:** `client/include/Havoc/Packager.hpp`

**Macros:**
- `HAVOC_PACKAGER_H` (line 2)

**Structs:**
- `Package` (line 27)

#### `PyAgentClass.hpp`
**Path:** `client/include/Havoc/PythonApi/PyAgentClass.hpp`

**Macros:**
- `HAVOC_PYAGENTCLASS_HPP` (line 2)
- `AllocMov` (line 5)

#### `PyDialogClass.hpp`
**Path:** `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

**Macros:**
- `HAVOC_PYDIALOGCLASS_H` (line 2)

#### `PyLoggerClass.hpp`
**Path:** `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

**Macros:**
- `HAVOC_PYLOGGERCLASS_H` (line 2)

#### `PyTreeClass.hpp`
**Path:** `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

**Macros:**
- `HAVOC_PYTREECLASS_H` (line 2)

#### `PyWidgetClass.hpp`
**Path:** `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

**Macros:**
- `HAVOC_PYWIDGETCLASS_H` (line 2)

#### `Service.hpp`
**Path:** `client/include/Havoc/Service.hpp`

**Macros:**
- `HAVOC_SERVICE_HPP` (line 2)

#### `About.hpp`
**Path:** `client/include/UserInterface/Dialogs/About.hpp`

**Classes:**
- `About` (line 7)

**Macros:**
- `HAVOC_ABOUTDIALOG_H` (line 2)

#### `Connect.hpp`
**Path:** `client/include/UserInterface/Dialogs/Connect.hpp`

**Macros:**
- `HAVOC_CONNECTDIALOG_H` (line 2)

#### `Listener.hpp`
**Path:** `client/include/UserInterface/Dialogs/Listener.hpp`

**Macros:**
- `HAVOC_LISTENER_HPP` (line 3)

#### `Payload.hpp`
**Path:** `client/include/UserInterface/Dialogs/Payload.hpp`

**Classes:**
- `Payload` (line 21)

**Macros:**
- `HAVOC_STAGELESSDIALOG_H` (line 2)

#### `HavocUI.hpp`
**Path:** `client/include/UserInterface/HavocUI.hpp`

**Macros:**
- `HAVOC_HAVOCUI_HPP` (line 2)

#### `EventViewer.hpp`
**Path:** `client/include/UserInterface/SmallWidgets/EventViewer.hpp`

**Macros:**
- `HAVOC_EVENTVIEWER_HPP` (line 2)

#### `Chat.hpp`
**Path:** `client/include/UserInterface/Widgets/Chat.hpp`

**Macros:**
- `HAVOC_CHATWIDGET_H` (line 2)

#### `FileBrowser.hpp`
**Path:** `client/include/UserInterface/Widgets/FileBrowser.hpp`

**Classes:**
- `FileBrowserTableItem` (line 40)
- `FileBrowserTreeItem` (line 46)
- `FileBrowser` (line 53)

**Macros:**
- `HAVOC_FILEBROWSER_HPP` (line 2)

**Structs:**
- `_FileDirData` (line 33)

#### `ListenerTable.hpp`
**Path:** `client/include/UserInterface/Widgets/ListenerTable.hpp`

*No symbols extracted*

#### `ProcessList.hpp`
**Path:** `client/include/UserInterface/Widgets/ProcessList.hpp`

**Macros:**
- `HAVOC_PROCESSLIST_HPP` (line 2)

#### `PythonScript.hpp`
**Path:** `client/include/UserInterface/Widgets/PythonScript.hpp`

**Macros:**
- `HAVOC_PYTHONSCRIPTWIDGET_HPP` (line 3)

#### `SessionGraph.hpp`
**Path:** `client/include/UserInterface/Widgets/SessionGraph.hpp`

**Classes:**
- `NodeItemType` (line 14)
- `Node` (line 20)
- `GraphWidget` (line 77)
- `Edge` (line 138)

**Functions:**
- `type` (line 52) `int type() const override`
- `type` (line 153) `int type() const override`

**Macros:**
- `HAVOC_SESSIONGRAPH_HPP` (line 2)

#### `SessionTable.hpp`
**Path:** `client/include/UserInterface/Widgets/SessionTable.hpp`

**Macros:**
- `HAVOC_SESSIONTABLE_HPP` (line 2)

#### `Store.hpp`
**Path:** `client/include/UserInterface/Widgets/Store.hpp`

**Classes:**
- `Store` (line 35)

**Macros:**
- `HAVOC_STORE_HPP` (line 2)

#### `Teamserver.hpp`
**Path:** `client/include/UserInterface/Widgets/Teamserver.hpp`

**Classes:**
- `Teamserver` (line 16)

**Macros:**
- `HAVOC_TEAMSERVER_HPP` (line 2)

#### `Base.hpp`
**Path:** `client/include/Util/Base.hpp`

**Macros:**
- `HAVOC_BASE_HPP` (line 2)

#### `global.hpp`
**Path:** `client/include/global.hpp`

**Macros:**
- `HAVOC_GLOBAL_HPP` (line 2)

**Structs:**
- `RegisteredCommand` (line 78)
- `RegisteredModule` (line 93)
- `ListenerItem` (line 106)
- `Listener` (line 145)

### PY (4 files)

#### `hash_func.py`
**Path:** `payloads/Demon/scripts/hash_func.py`

**Functions:**
- `hash_string` (line 7) `def hash_string(string)`
- `hash_coffapi` (line 18) `def hash_coffapi(string)`

#### `extract.py`
**Path:** `payloads/DllLdr/Scripts/extract.py`

**Functions:**
- `main` (line 8) `def main(options)`

#### `extract.py`
**Path:** `payloads/Shellcode/Scripts/extract.py`

*No symbols extracted*

#### `conf.py`
**Path:** `teamserver/pkg/profile/yaotl/guide/conf.py`

*No symbols extracted*

### S (2 files)

#### `Asm.s`
**Path:** `payloads/Shellcode/Source/Asm/x64/Asm.s`

*No symbols extracted*

#### `Asm.s`
**Path:** `payloads/Shellcode/Source/Asm/x86/Asm.s`

*No symbols extracted*

### SH (1 files)

#### `Install.sh`
**Path:** `teamserver/Install.sh`

*No symbols extracted*
