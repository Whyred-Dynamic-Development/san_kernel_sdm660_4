ifeq ($(CONFIG_XIAOMI_WHYRED),y)
dtb-$(CONFIG_XIAOMI_WHYRED) := whyred.dtb
else
ifeq ($(CONFIG_XIAOMI_TULIP),y)
dtb-$(CONFIG_XIAOMI_TULIP) := tulip.dtb
else
dtb-$(CONFIG_ARCH_SDM660) += sdm660-sim.dtb \
sdm660-internal-codec-cdp.dtb \
        sdm660-internal-codec-mtp.dtb \
        sdm660-internal-codec-rcm.dtb \
        sdm660-cdp.dtb \
        sdm660-mtp.dtb \
        sdm660-qrd.dtb \
        sdm660-rcm.dtb \
        sdm660-pm660a-cdp.dtb \
        sdm660-pm660a-mtp.dtb \
        sdm660-pm660a-qrd.dtb \
        sdm660-pm660a-rcm.dtb \
        sdm660-internal-codec-pm660a-cdp.dtb \
        sdm660-internal-codec-pm660a-mtp.dtb \
        sdm660-internal-codec-pm660a-rcm.dtb \
        sdm660-pm660a-sim.dtb \
        sda660-cdp.dtb \
        sda660-mtp.dtb \
        sda660-rcm.dtb \
        sda660-pm660a-cdp.dtb \
        sda660-pm660a-mtp.dtb \
        sda660-pm660a-rcm.dtb \
        sda660-pm660a-qrd-hdk.dtb \
        sdm660-headset-jacktype-no-cdp.dtb \
        sdm660-headset-jacktype-no-rcm.dtb \
        sdm660-pm660a-headset-jacktype-no-cdp.dtb \
        sdm660-pm660a-headset-jacktype-no-rcm.dtb \
        sdm660-usbc-audio-mtp.dtb \
        sdm660-usbc-audio-rcm.dtb \
        sdm636-cdp.dtb \
        sdm636-mtp.dtb \
        sdm636-qrd.dtb \
        sdm636-rcm.dtb \
        sdm636-headset-jacktype-no-cdp.dtb \
        sdm636-headset-jacktype-no-rcm.dtb \
        sdm636-internal-codec-cdp.dtb \
        sdm636-internal-codec-mtp.dtb \
        sdm636-internal-codec-pm660a-cdp.dtb \
        sdm636-internal-codec-pm660a-mtp.dtb \
        sdm636-internal-codec-pm660a-rcm.dtb \
        sdm636-internal-codec-rcm.dtb \
        sdm636-pm660a-headset-jacktype-no-cdp.dtb \
        sdm636-pm660a-headset-jacktype-no-rcm.dtb \
        sdm636-pm660a-cdp.dtb \
        sdm636-pm660a-mtp.dtb \
        sdm636-pm660a-qrd.dtb \
        sdm636-pm660a-rcm.dtb \
        sdm636-usbc-audio-mtp.dtb \
        sdm636-usbc-audio-rcm.dtb
endif
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
