# Copyright (C) 2007-2013 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( luassert NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( luassert.state src/state.lua )
install_lua_module ( luassert.util src/util.lua )
install_lua_module ( luassert.spy src/spy.lua )
install_lua_module ( luassert.stub src/stub.lua )
install_lua_module ( luassert.assert src/assert.lua )
install_lua_module ( luassert.modifiers src/modifiers.lua )
install_lua_module ( luassert.assertions src/assertions.lua )
install_lua_module ( luassert.mock src/mock.lua )
install_lua_module ( luassert.init src/init.lua )
install_lua_module ( luassert.formatters.init src/formatters/init.lua )
install_lua_module ( luassert.formatters.binarystring src/formatters/binarystring.lua )
install_lua_module ( luassert.languages.en src/languages/en.lua )
install_lua_module ( luassert.languages.ar src/languages/ar.lua )
install_lua_module ( luassert.languages.fr src/languages/fr.lua )
install_lua_module ( luassert.languages.nl src/languages/nl.lua )
install_lua_module ( luassert.languages.ru src/languages/ru.lua )
install_lua_module ( luassert.languages.ua src/languages/ua.lua )
install_lua_module ( luassert.languages.zh src/languages/zh.lua )

install_data ( README.md LICENSE CONTRIBUTING.md )
