# Note: the handlers are inserted automatically
# via a GCC constructor. To work, the linker should
# not drop the handler if it is not called.
# Handler can be called dynamically based
# on the received image type.
obj-$(CONFIG_ARCHIVE) += archive_handler.o
obj-$(CONFIG_CFI)	+= flash_handler.o
obj-$(CONFIG_RAW)	+= raw_handler.o
obj-$(CONFIG_UBIVOL)	+= ubivol_handler.o
obj-$(CONFIG_LUASCRIPTHANDLER) += lua_scripthandler.o
obj-$(CONFIG_SHELLSCRIPTHANDLER) += shell_scripthandler.o
obj-$(CONFIG_RAW) += raw_handler.o
obj-$(CONFIG_REMOTE_HANDLER) += remote_handler.o
obj-$(CONFIG_UBOOT) += uboot_handler.o
