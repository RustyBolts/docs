// ./components/PasswordGate.jsx
import { useState } from "react";

export default function PasswordGate({ children }) {
  const [authenticated, setAuthenticated] = useState(
    typeof window !== "undefined" && sessionStorage.getItem("auth") === "true"
  );
  const [password, setPassword] = useState("");

  const handleLogin = (e) => {
    e.preventDefault();
    if (password === "YOUR_SECRET_PASSWORD") {
      sessionStorage.setItem("auth", "true");
      setAuthenticated(true);
    } else {
      alert("密碼錯誤");
    }
  };

  if (!authenticated) {
    return (
      <div style={{ textAlign: "center", marginTop: "100px" }}>
        <h2>請輸入密碼以繼續</h2>
        <form onSubmit={handleLogin}>
          <input
            type="password"
            placeholder="Password"
            value={password}
            onChange={(e) => setPassword(e.target.value)}
          />
          <button type="submit">登入</button>
        </form>
      </div>
    );
  }

  return <>{children}</>;
}