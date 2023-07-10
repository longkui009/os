 if (mconfig.build_os != "Darwin") {
        mconfig.build_ldflags += ["-Wl,--gc-sections"];
        mconfig.stripflags += ["-p"];
    }
