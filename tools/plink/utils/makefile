LIBRARY=libutils

ifeq ($(MAKESERVER),1)
$(error Please do not specify MAKESERVER=1 on the command line or as environment variable)
endif

DEFINES += SECURITY_WIN32
INCLUDES := .. ../windows $(INCLUDES) ../terminal

CSRCS = base64_decode_atom.c \
 base64_encode_atom.c \
 bufchain.c \
 buildinfo.c \
 burnstr.c \
 chomp.c \
 conf.c \
 conf_dest.c \
 conf_launchable.c \
 ctrlparse.c \
 debug.c \
 dupcat.c \
 dupprintf.c \
 dupstr.c \
 encode_utf8.c \
 host_strchr.c \
 host_strchr_internal.c \
 host_strcspn.c \
 host_strduptrim.c \
 host_strrchr.c \
 ltime.c \
 marshal.c \
 memory.c \
 memxor.c \
 null_lp.c \
 nullseat.c \
 nullstrcmp.c \
 out_of_memory.c \
 parse_blocksize.c \
 prompts.c \
 ptrlen.c \
 read_file_into.c \
 seat_connection_fatal.c \
 sessprep.c \
 sk_free_peer_info.c \
 smemclr.c \
 smemeq.c \
 ssh2_pick_fingerprint.c \
 sshutils.c \
 strbuf.c \
 string_length_for_printf.c \
 stripctrl.c \
 tree234.c \
 validate_manual_hostkey.c \
 version.c \
 wcwidth.c \
 wildcard.c \
 write_c_string_literal.c \
 x11_dehexify.c \
 x11_identify_auth_proto.c \
 x11_make_greeting.c \
 x11_parse_ip.c \
 x11authfile.c \
 x11authnames.c \
 antispoof.c \
 tempseat.c \
 fgetline.c \
 default_description.c \
 log_proxy_stderr.c \
 spr_get_error_message.c \
 make_spr_sw_abort_static.c \
 dup_mb_to_wc.c

