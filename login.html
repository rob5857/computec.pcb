import React, { useState } from 'react';
import { X, Mail, Lock, User, Eye, EyeOff, LogIn, UserPlus, Chrome, Github } from 'lucide-react';

const PCBLoginSystem = () => {
  const [showLogin, setShowLogin] = useState(false);
  const [showRegister, setShowRegister] = useState(false);
  const [showPassword, setShowPassword] = useState(false);
  const [showConfirmPassword, setShowConfirmPassword] = useState(false);
  
  const [loginData, setLoginData] = useState({
    email: '',
    password: ''
  });
  
  const [registerData, setRegisterData] = useState({
    name: '',
    email: '',
    password: '',
    confirmPassword: ''
  });

  const [loginError, setLoginError] = useState('');
  const [registerError, setRegisterError] = useState('');

  const handleLogin = () => {
    setLoginError('');
    
    if (!loginData.email || !loginData.password) {
      setLoginError('Por favor completa todos los campos');
      return;
    }
    
    if (!loginData.email.includes('@')) {
      setLoginError('Email inválido');
      return;
    }
    
    console.log('Login attempt:', loginData);
    alert('Login exitoso! (Conecta con tu API)');
    setShowLogin(false);
  };

  const handleRegister = () => {
    setRegisterError('');
    
    if (!registerData.name || !registerData.email || !registerData.password || !registerData.confirmPassword) {
      setRegisterError('Por favor completa todos los campos');
      return;
    }
    
    if (!registerData.email.includes('@')) {
      setRegisterError('Email inválido');
      return;
    }
    
    if (registerData.password.length < 8) {
      setRegisterError('La contraseña debe tener al menos 8 caracteres');
      return;
    }
    
    if (registerData.password !== registerData.confirmPassword) {
      setRegisterError('Las contraseñas no coinciden');
      return;
    }
    
    console.log('Register attempt:', registerData);
    alert('Registro exitoso! (Conecta con tu API)');
    setShowRegister(false);
  };

  const handleOAuthLogin = (provider) => {
    console.log(`OAuth login with ${provider}`);
    alert(`Conectando con ${provider}... (Implementa OAuth)`);
  };

  const handleKeyPress = (e, action) => {
    if (e.key === 'Enter') {
      action();
    }
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-900 via-purple-900 to-indigo-900 flex items-center justify-center p-4">
      <div className="max-w-6xl w-full">
        <div className="bg-white/10 backdrop-blur-lg rounded-2xl p-8 border border-white/20">
          <h1 className="text-4xl font-bold text-white mb-4">PCB System Dashboard</h1>
          <p className="text-blue-200 mb-8">Sistema de gestión de PCB con autenticación avanzada</p>
          
          <div className="flex gap-4 flex-wrap">
            <button
              onClick={() => setShowLogin(true)}
              className="px-8 py-3 bg-blue-600 hover:bg-blue-700 text-white font-semibold rounded-lg flex items-center gap-2 transition-all shadow-lg hover:shadow-xl"
            >
              <LogIn className="w-5 h-5" />
              Iniciar Sesión
            </button>
            
            <button
              onClick={() => setShowRegister(true)}
              className="px-8 py-3 bg-purple-600 hover:bg-purple-700 text-white font-semibold rounded-lg flex items-center gap-2 transition-all shadow-lg hover:shadow-xl"
            >
              <UserPlus className="w-5 h-5" />
              Registrarse
            </button>
          </div>
        </div>
      </div>

      {showLogin && (
        <div className="fixed inset-0 bg-black/60 backdrop-blur-sm flex items-center justify-center p-4 z-50 animate-fadeIn">
          <div className="bg-gradient-to-br from-slate-800 to-slate-900 rounded-2xl p-8 max-w-md w-full border border-white/20 shadow-2xl relative animate-slideUp">
            <button
              onClick={() => setShowLogin(false)}
              className="absolute top-4 right-4 text-gray-400 hover:text-white transition-colors"
            >
              <X className="w-6 h-6" />
            </button>

            <div className="text-center mb-6">
              <div className="w-16 h-16 bg-blue-600 rounded-full flex items-center justify-center mx-auto mb-4">
                <LogIn className="w-8 h-8 text-white" />
              </div>
              <h2 className="text-3xl font-bold text-white mb-2">Iniciar Sesión</h2>
              <p className="text-gray-400">Accede a tu cuenta de PCB System</p>
            </div>

            {loginError && (
              <div className="mb-4 p-3 bg-red-500/20 border border-red-500/50 rounded-lg text-red-200 text-sm">
                {loginError}
              </div>
            )}

            <div className="space-y-4">
              <div>
                <label className="block text-gray-300 mb-2 font-medium">Email</label>
                <div className="relative">
                  <Mail className="absolute left-3 top-1/2 transform -translate-y-1/2 w-5 h-5 text-gray-400" />
                  <input
                    type="email"
                    value={loginData.email}
                    onChange={(e) => setLoginData({...loginData, email: e.target.value})}
                    onKeyPress={(e) => handleKeyPress(e, handleLogin)}
                    placeholder="tu@email.com"
                    className="w-full pl-12 pr-4 py-3 bg-white/10 border border-white/20 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-blue-500 transition-all"
                  />
                </div>
              </div>

              <div>
                <label className="block text-gray-300 mb-2 font-medium">Contraseña</label>
                <div className="relative">
                  <Lock className="absolute left-3 top-1/2 transform -translate-y-1/2 w-5 h-5 text-gray-400" />
                  <input
                    type={showPassword ? "text" : "password"}
                    value={loginData.password}
                    onChange={(e) => setLoginData({...loginData, password: e.target.value})}
                    onKeyPress={(e) => handleKeyPress(e, handleLogin)}
                    placeholder="••••••••"
                    className="w-full pl-12 pr-12 py-3 bg-white/10 border border-white/20 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-blue-500 transition-all"
                  />
                  <button
                    type="button"
                    onClick={() => setShowPassword(!showPassword)}
                    className="absolute right-3 top-1/2 transform -translate-y-1/2 text-gray-400 hover:text-white transition-colors"
                  >
                    {showPassword ? <EyeOff className="w-5 h-5" /> : <Eye className="w-5 h-5" />}
                  </button>
                </div>
              </div>

              <div className="text-right">
                <button type="button" className="text-blue-400 hover:text-blue-300 text-sm transition-colors">
                  ¿Olvidaste tu contraseña?
                </button>
              </div>

              <button
                onClick={handleLogin}
                className="w-full py-3 bg-blue-600 hover:bg-blue-700 text-white font-semibold rounded-lg transition-all shadow-lg hover:shadow-xl"
              >
                Iniciar Sesión
              </button>
            </div>

            <div className="flex items-center gap-4 my-6">
              <div className="flex-1 h-px bg-white/20"></div>
              <span className="text-gray-400 text-sm">O continúa con</span>
              <div className="flex-1 h-px bg-white/20"></div>
            </div>

            <div className="grid grid-cols-2 gap-3">
              <button
                onClick={() => handleOAuthLogin('Google')}
                className="py-3 bg-white/10 hover:bg-white/20 border border-white/20 rounded-lg flex items-center justify-center gap-2 text-white transition-all"
              >
                <Chrome className="w-5 h-5" />
                Google
              </button>
              <button
                onClick={() => handleOAuthLogin('GitHub')}
                className="py-3 bg-white/10 hover:bg-white/20 border border-white/20 rounded-lg flex items-center justify-center gap-2 text-white transition-all"
              >
                <Github className="w-5 h-5" />
                GitHub
              </button>
            </div>

            <div className="text-center mt-6">
              <p className="text-gray-400">
                ¿No tienes cuenta?{' '}
                <button
                  onClick={() => {
                    setShowLogin(false);
                    setShowRegister(true);
                  }}
                  className="text-blue-400 hover:text-blue-300 font-semibold transition-colors"
                >
                  Regístrate aquí
                </button>
              </p>
            </div>
          </div>
        </div>
      )}

      {showRegister && (
        <div className="fixed inset-0 bg-black/60 backdrop-blur-sm flex items-center justify-center p-4 z-50 animate-fadeIn">
          <div className="bg-gradient-to-br from-slate-800 to-slate-900 rounded-2xl p-8 max-w-md w-full border border-white/20 shadow-2xl relative animate-slideUp">
            <button
              onClick={() => setShowRegister(false)}
              className="absolute top-4 right-4 text-gray-400 hover:text-white transition-colors"
            >
              <X className="w-6 h-6" />
            </button>

            <div className="text-center mb-6">
              <div className="w-16 h-16 bg-purple-600 rounded-full flex items-center justify-center mx-auto mb-4">
                <UserPlus className="w-8 h-8 text-white" />
              </div>
              <h2 className="text-3xl font-bold text-white mb-2">Crear Cuenta</h2>
              <p className="text-gray-400">Únete a PCB System hoy</p>
            </div>

            {registerError && (
              <div className="mb-4 p-3 bg-red-500/20 border border-red-500/50 rounded-lg text-red-200 text-sm">
                {registerError}
              </div>
            )}

            <div className="space-y-4">
              <div>
                <label className="block text-gray-300 mb-2 font-medium">Nombre Completo</label>
                <div className="relative">
                  <User className="absolute left-3 top-1/2 transform -translate-y-1/2 w-5 h-5 text-gray-400" />
                  <input
                    type="text"
                    value={registerData.name}
                    onChange={(e) => setRegisterData({...registerData, name: e.target.value})}
                    onKeyPress={(e) => handleKeyPress(e, handleRegister)}
                    placeholder="Juan Pérez"
                    className="w-full pl-12 pr-4 py-3 bg-white/10 border border-white/20 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                  />
                </div>
              </div>

              <div>
                <label className="block text-gray-300 mb-2 font-medium">Email</label>
                <div className="relative">
                  <Mail className="absolute left-3 top-1/2 transform -translate-y-1/2 w-5 h-5 text-gray-400" />
                  <input
                    type="email"
                    value={registerData.email}
                    onChange={(e) => setRegisterData({...registerData, email: e.target.value})}
                    onKeyPress={(e) => handleKeyPress(e, handleRegister)}
                    placeholder="tu@email.com"
                    className="w-full pl-12 pr-4 py-3 bg-white/10 border border-white/20 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                  />
                </div>
              </div>

              <div>
                <label className="block text-gray-300 mb-2 font-medium">Contraseña</label>
                <div className="relative">
                  <Lock className="absolute left-3 top-1/2 transform -translate-y-1/2 w-5 h-5 text-gray-400" />
                  <input
                    type={showPassword ? "text" : "password"}
                    value={registerData.password}
                    onChange={(e) => setRegisterData({...registerData, password: e.target.value})}
                    onKeyPress={(e) => handleKeyPress(e, handleRegister)}
                    placeholder="Mínimo 8 caracteres"
                    className="w-full pl-12 pr-12 py-3 bg-white/10 border border-white/20 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                  />
                  <button
                    type="button"
                    onClick={() => setShowPassword(!showPassword)}
                    className="absolute right-3 top-1/2 transform -translate-y-1/2 text-gray-400 hover:text-white transition-colors"
                  >
                    {showPassword ? <EyeOff className="w-5 h-5" /> : <Eye className="w-5 h-5" />}
                  </button>
                </div>
              </div>

              <div>
                <label className="block text-gray-300 mb-2 font-medium">Confirmar Contraseña</label>
                <div className="relative">
                  <Lock className="absolute left-3 top-1/2 transform -translate-y-1/2 w-5 h-5 text-gray-400" />
                  <input
                    type={showConfirmPassword ? "text" : "password"}
                    value={registerData.confirmPassword}
                    onChange={(e) => setRegisterData({...registerData, confirmPassword: e.target.value})}
                    onKeyPress={(e) => handleKeyPress(e, handleRegister)}
                    placeholder="Repite tu contraseña"
                    className="w-full pl-12 pr-12 py-3 bg-white/10 border border-white/20 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                  />
                  <button
                    type="button"
                    onClick={() => setShowConfirmPassword(!showConfirmPassword)}
                    className="absolute right-3 top-1/2 transform -translate-y-1/2 text-gray-400 hover:text-white transition-colors"
                  >
                    {showConfirmPassword ? <EyeOff className="w-5 h-5" /> : <Eye className="w-5 h-5" />}
                  </button>
                </div>
              </div>

              <button
                onClick={handleRegister}
                className="w-full py-3 bg-purple-600 hover:bg-purple-700 text-white font-semibold rounded-lg transition-all shadow-lg hover:shadow-xl"
              >
                Crear Cuenta
              </button>
            </div>

            <div className="flex items-center gap-4 my-6">
              <div className="flex-1 h-px bg-white/20"></div>
              <span className="text-gray-400 text-sm">O regístrate con</span>
              <div className="flex-1 h-px bg-white/20"></div>
            </div>

            <div className="grid grid-cols-2 gap-3">
              <button
                onClick={() => handleOAuthLogin('Google')}
                className="py-3 bg-white/10 hover:bg-white/20 border border-white/20 rounded-lg flex items-center justify-center gap-2 text-white transition-all"
              >
                <Chrome className="w-5 h-5" />
                Google
              </button>
              <button
                onClick={() => handleOAuthLogin('GitHub')}
                className="py-3 bg-white/10 hover:bg-white/20 border border-white/20 rounded-lg flex items-center justify-center gap-2 text-white transition-all"
              >
                <Github className="w-5 h-5" />
                GitHub
              </button>
            </div>

            <div className="text-center mt-6">
              <p className="text-gray-400">
                ¿Ya tienes cuenta?{' '}
                <button
                  onClick={() => {
                    setShowRegister(false);
                    setShowLogin(true);
                  }}
                  className="text-purple-400 hover:text-purple-300 font-semibold transition-colors"
                >
                  Inicia sesión
                </button>
              </p>
            </div>
          </div>
        </div>
      )}

      <style>{`
        @keyframes fadeIn {
          from { opacity: 0; }
          to { opacity: 1; }
        }
        
        @keyframes slideUp {
          from {
            opacity: 0;
            transform: translateY(20px);
          }
          to {
            opacity: 1;
            transform: translateY(0);
          }
        }
        
        .animate-fadeIn {
          animation: fadeIn 0.2s ease-out;
        }
        
        .animate-slideUp {
          animation: slideUp 0.3s ease-out;
        }
      `}</style>
    </div>
  );
};

export default PCBLoginSystem;
