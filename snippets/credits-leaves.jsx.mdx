export const FloatingLeaves = () => {
  const names = [
    "Jigawok/Mckrieg",
    "Laskt",
    "Varnock",
    "Feng",
    "Ragingfire",
    "Boonslayer",
    "Mirai",
    "Cajender",
    "Oddy",
    "Cole",
    "Narrator",
    "Kili",
    "Hawke",
    "Pierogidude9411",
    "Takuto",
    "Zygard",
    "IronMad108",
    "Adam500",
    "Akio",
    "Amalkamis",
    "Antares",
    "Ashley",
    "Ashton",
    "Chase",
    "Cain",
    "Chiotuz",
    "CrushU",
    "Elegard",
    "Erra",
    "Jewel",
    "Jondd23",
    "Kask",
    "Kalypso",
    "Kaiya Silverthorn",
    "Lana",
    "Marcemallow",
    "Mark",
    "Marquez",
    "MechaX",
    "Minzara",
    "Mortimer De La Vigo",
    "Mourdos",
    "Mosano",
    "PipSqueak",
    "Ralphp",
    "Recludere",
    "Rusty",
    "Seishinryoku",
    "Seraph",
    "Sestren",
    "Sexy Bob",
    "Shadow",
    "Shigeo",
    "Snark",
    "SoulGambit",
    "Splatterk",
    "Tark",
    "Terrato",
    "TheOracle",
    "Thinkalot",
    "TR",
    "Trister",
    "Vatoreus",
    "Xeno",
    "Xeriar",
    "Yukino",
    "Zeke",
  ];

  const [bursts, setBursts] = useState({});
  const [hovered, setHovered] = useState(null);
  const idRef = useRef(0);

  const handleClick = (name) => {
    idRef.current += 1;
    const burstId = idRef.current;
    // 12 petals shooting outward at random angles
    const petals = Array.from({ length: 12 }).map((_, i) => {
      const angle = (i / 12) * Math.PI * 2 + Math.random() * 0.4;
      const dist = 60 + Math.random() * 50;
      return {
        id: i,
        dx: Math.cos(angle) * dist,
        dy: Math.sin(angle) * dist,
        rot: (Math.random() - 0.5) * 720,
        delay: Math.random() * 80,
      };
    });
    setBursts((b) => ({ ...b, [name]: { id: burstId, petals } }));
    setTimeout(() => {
      setBursts((b) => {
        const cur = b[name];
        if (!cur || cur.id !== burstId) return b;
        const next = { ...b };
        delete next[name];
        return next;
      });
    }, 1700);
  };

  return (
    <div
      className="not-prose"
      style={{
        position: "relative",
        width: "100%",
        padding: "40px 32px 44px",
        borderRadius: "18px",
        background:
          "radial-gradient(ellipse at 20% 0%, rgba(76, 130, 86, 0.28), transparent 55%), radial-gradient(ellipse at 80% 100%, rgba(40, 80, 55, 0.35), transparent 55%), linear-gradient(180deg, #0d1a12 0%, #0a1410 100%)",
        border: "1px solid rgba(180, 200, 170, 0.18)",
        boxShadow:
          "inset 0 1px 0 rgba(220, 230, 200, 0.06), 0 20px 60px -30px rgba(0, 0, 0, 0.6)",
        overflow: "hidden",
      }}
    >
      {/* Keyframes injected once */}
      <style>{`
        @keyframes shotai-petal-fly {
          0%   { opacity: 0; transform: translate(-50%, -50%) rotate(0deg) scale(0.4); }
          15%  { opacity: 1; }
          100% { opacity: 0; transform: translate(calc(-50% + var(--dx)), calc(-50% + var(--dy))) rotate(var(--rot)) scale(1); }
        }
        @keyframes shotai-ring-expand {
          0%   { opacity: 0.9; transform: translate(-50%, -50%) scale(0.2); }
          100% { opacity: 0; transform: translate(-50%, -50%) scale(3.2); }
        }
        @keyframes shotai-name-flare {
          0%   { transform: translateY(0) scale(1); }
          30%  { transform: translateY(-3px) scale(1.14); }
          100% { transform: translateY(0) scale(1); }
        }
      `}</style>

      {/* Header */}
      <div
        style={{
          display: "flex",
          alignItems: "center",
          justifyContent: "center",
          gap: "14px",
          marginBottom: "30px",
        }}
      >
        <span
          style={{
            flex: 1,
            height: "1px",
            background:
              "linear-gradient(90deg, transparent, rgba(200, 220, 180, 0.35), transparent)",
          }}
        />
        <span
          style={{
            fontFamily:
              "'Cormorant Garamond', 'Playfair Display', Georgia, serif",
            fontStyle: "italic",
            fontSize: "18px",
            letterSpacing: "0.18em",
            textTransform: "uppercase",
            color: "rgba(220, 230, 200, 0.85)",
          }}
        >
          ✦ Roll of Honor ✦
        </span>
        <span
          style={{
            flex: 1,
            height: "1px",
            background:
              "linear-gradient(90deg, transparent, rgba(200, 220, 180, 0.35), transparent)",
          }}
        />
      </div>

      {/* Name grid */}
      <div
        style={{
          display: "grid",
          gridTemplateColumns: "repeat(auto-fill, minmax(180px, 1fr))",
          gap: "14px 24px",
          justifyItems: "center",
        }}
      >
        {names.map((name) => {
          const burst = bursts[name];
          const isBursting = !!burst;
          const isHover = hovered === name;
          return (
            <button
              key={name}
              onClick={() => handleClick(name)}
              onMouseEnter={() => setHovered(name)}
              onMouseLeave={() => setHovered(null)}
              style={{
                position: "relative",
                background: "transparent",
                border: "none",
                padding: "10px 8px",
                cursor: "pointer",
                fontFamily:
                  "'Cormorant Garamond', 'Playfair Display', Georgia, serif",
                fontSize: "18px",
                fontWeight: 500,
                letterSpacing: "0.04em",
                color: isBursting
                  ? "#fff6d0"
                  : isHover
                  ? "#eef7d8"
                  : "rgba(225, 232, 210, 0.9)",
                textShadow: isBursting
                  ? "0 0 10px rgba(255, 230, 150, 0.95), 0 0 24px rgba(255, 210, 120, 0.65), 0 0 46px rgba(255, 200, 100, 0.4)"
                  : isHover
                  ? "0 0 8px rgba(200, 230, 170, 0.55)"
                  : "0 1px 2px rgba(0,0,0,0.5)",
                transition:
                  "color 0.35s ease, text-shadow 0.5s ease",
                whiteSpace: "nowrap",
                overflow: "visible",
                maxWidth: "100%",
                animation: isBursting
                  ? "shotai-name-flare 0.9s ease-out"
                  : "none",
              }}
            >
              <span style={{ position: "relative", zIndex: 2 }}>{name}</span>

              {/* underline shimmer on hover */}
              <span
                style={{
                  position: "absolute",
                  left: "50%",
                  bottom: "4px",
                  transform: "translateX(-50%)",
                  width: isHover || isBursting ? "70%" : "0%",
                  height: "1px",
                  background: isBursting
                    ? "linear-gradient(90deg, transparent, rgba(255,220,140,0.95), transparent)"
                    : "linear-gradient(90deg, transparent, rgba(200,220,170,0.7), transparent)",
                  transition: "width 0.35s ease",
                  zIndex: 1,
                }}
              />

              {/* expanding ring */}
              {isBursting && (
                <span
                  style={{
                    position: "absolute",
                    left: "50%",
                    top: "50%",
                    width: "60px",
                    height: "60px",
                    borderRadius: "9999px",
                    border: "1px solid rgba(255, 220, 140, 0.7)",
                    boxShadow:
                      "0 0 20px rgba(255, 210, 120, 0.5), inset 0 0 20px rgba(255, 210, 120, 0.35)",
                    pointerEvents: "none",
                    animation: "shotai-ring-expand 1.3s ease-out forwards",
                    zIndex: 0,
                  }}
                />
              )}

              {/* petal burst */}
              {isBursting &&
                burst.petals.map((p) => (
                  <span
                    key={p.id}
                    style={{
                      position: "absolute",
                      left: "50%",
                      top: "50%",
                      width: "10px",
                      height: "14px",
                      borderRadius: "50% 10% 50% 10%",
                      background:
                        "linear-gradient(140deg, #d9f0b3 0%, #7cbf6a 60%, #3f7a3f 100%)",
                      boxShadow:
                        "0 0 8px rgba(180, 240, 160, 0.6), 0 0 16px rgba(120, 200, 120, 0.35)",
                      pointerEvents: "none",
                      // custom props consumed by keyframes
                      "--dx": `${p.dx}px`,
                      "--dy": `${p.dy}px`,
                      "--rot": `${p.rot}deg`,
                      animation: `shotai-petal-fly 1.5s ease-out ${p.delay}ms forwards`,
                      zIndex: 3,
                    }}
                  />
                ))}
            </button>
          );
        })}
      </div>

      {/* Footer */}
      <div
        style={{
          display: "flex",
          alignItems: "center",
          justifyContent: "center",
          gap: "14px",
          marginTop: "34px",
          color: "rgba(200, 220, 180, 0.5)",
          fontSize: "12px",
          letterSpacing: "0.24em",
          textTransform: "uppercase",
          fontFamily: "'Cormorant Garamond', Georgia, serif",
          fontStyle: "italic",
        }}
      >
        <span
          style={{
            flex: 1,
            height: "1px",
            background:
              "linear-gradient(90deg, transparent, rgba(200, 220, 180, 0.25), transparent)",
          }}
        />
        <span>tap a name to honor it</span>
        <span
          style={{
            flex: 1,
            height: "1px",
            background:
              "linear-gradient(90deg, transparent, rgba(200, 220, 180, 0.25), transparent)",
          }}
        />
      </div>
    </div>
  );
};
